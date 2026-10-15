# 智能母线系统横向对比

## 对比口径

本表基于厂商公开页面和产品资料做定性对照，关注母线系统在“本体、感知、模型、分析、执行、集成”六个层级的能力。`✓` 表示公开资料中已有成熟产品路径，`△` 表示依配置、平台或项目实施而定。

| 能力 | Siemens SIVACON 8PS | Schneider Canalis + PME | Eaton XAP Track / Exertherm | 国内常见方案 | BusGuard Agent |
| --- | --- | --- | --- | --- | --- |
| 模块化母线与扩展 | ✓ 多系列、BIM 规划 | ✓ KS / KSA 等系列 | ✓ 轨道式与紧凑型 | ✓ 型号较多 | ✓ 继承辉虹产品族，做工程化适配 |
| 电气量与能效 | ✓ Powerline / 能源管理 | ✓ EcoStruxure 监测 | ✓ 功率质量与第三方集成 | ✓ 电压、电流、功率、电能 | ✓ 电气量 + 负载画像 + 回路健康分 |
| 接头级连续测温 | △ 依产品和选配 | ✓ 热监测应用 | ✓ 接头级连续监测 | ✓ 4 / 8 路温度模块常见 | ✓ 测点、相别、区段一体化建模 |
| 数字孪生 / BIM | ✓ SIMARIS + as-built | △ 依配置 | △ 以监测和平台为主 | △ 图形化视图逐步普及 | ✓ 透明三维拓扑和资产定位 |
| 预测诊断 | △ 偏系统集成 | △ 偏规则与趋势 | ✓ 热趋势与故障定位 | △ 告警与阈值为主 | ✓ 趋势外推 + 根因证据链 + 建议动作 |
| 工单运维闭环 | △ 需接入上层系统 | △ 依平台与实施 | △ 强调告警与集成 | △ HMI / 云平台为主 | ✓ 告警 → 工单 → 处置 → 复测 |
| 开放集成 | ✓ 生态成熟，实施成本较高 | ✓ 生态成熟 | ✓ 支持 Modbus / EPMS / SCADA | ✓ 本地协议与云平台并存 | ✓ Modbus TCP / MQTT / REST 适配路线 |

## 设计结论

- 对辉虹最有价值的差异点是“接头级测温 + 数字孪生 + 可审计运维闭环”的组合，而不是单点增加一个告警页面。
- 产品应保留硬件中立的接入层，支持新建母线和既有母线改造两条交付路线。
- 预测模型必须绑定证据和动作，输出“为什么、影响哪里、下一步谁来做、做完如何验证”。
- 对外材料要把“能力对标”与“项目实际配置”分开表达，避免把选配能力写成默认能力。

## 公开参考

- [Siemens SIVACON 8PS](https://www.siemens.com/global/en/products/energy/low-voltage/systems/sivacon.html)
- [Schneider Electric 低压母线热监测](https://product-help.schneider-electric.com/EcoStruxure/Power-Monitoring-Expert-2024/content/applications/thermal_monitoring_-_lv_busway/operation/lvbw-operation.htm)
- [Eaton XAP Series Busway](https://www.eaton.com/au/en-gb/catalog/low-voltage-power-distribution-controls-systems/xap-series-busway.html)
- [Eaton XAPTrack Series Busway](https://www.eaton.com/content/dam/eaton/products/low-voltage-power-distribution-controls-systems/eatonbusbar/xap-track/xap-track-busway.pdf)

