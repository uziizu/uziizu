# BusGuard Agent
## 镇江辉虹智能母线健康智能体 · 产品介绍材料

### 一句话定位

把母线槽从“输配电部件”升级为“持续感知、趋势判断、主动派单、结果复核”的智能基础设施。

### 项目背景

母线故障通常集中在连接器、插接箱触点、始端箱和负载变化明显的区段。传统方式依赖定期巡检和人工判断，数据分散，隐患发现晚，处置结果也很难沉淀。BusGuard Agent 以回路、区段、测点和相别为统一资产语言，把现场状态变成可定位、可追踪、可审计的信息。

### 产品组成

| 层级 | 主要能力 | 交付结果 |
| --- | --- | --- |
| 感知层 | 接头级温度、电流、电压、负载、环境数据 | 形成可持续采样的测点网络 |
| 模型层 | 回路、区段、节点、A/B/C/N/PE 分相资产模型 | 建立可定位的数字孪生 |
| 分析层 | 阈值、趋势外推、健康分、根因证据链 | 给出风险等级和处置建议 |
| 执行层 | 告警、工单、派单、复测、关闭 | 形成完整运维闭环 |
| 交互层 | 总览大屏、节点详情、导体明细、自然语言问答 | 让管理者和现场人员共用一套事实 |

### 本项目原型指标

- 3 条回路、18 个区段、27 个测点
- A / B / C / N / PE 五线分相展示
- 透明三维拓扑，支持楼层、回路、相别定位
- 预警工作台支持一键生成维修工单
- 每个异常点保留趋势、根因、建议动作与复测结果

### 横向观察

公开资料显示，Siemens SIVACON 8PS 的优势在于数字孪生、BIM 规划和电力线载波；Schneider Canalis 与 EcoStruxure 侧重热监测和能源管理；Eaton XAP Track / Exertherm 强调接头级连续测温、故障定位和平台接入；国内常见方案普遍覆盖温度、电气量、本地 HMI 或云平台。BusGuard Agent 的产品机会在于把这些分散能力收敛为一条面向项目交付的“感知 → 判断 → 执行 → 复核”链路。

### 产品设计取舍

1. **先把接头级测温做成标准模块**：连接器、插接箱触点、始端箱优先，兼顾新建和改造项目。
2. **把数字孪生绑定竣工资料**：从 BIM / CAD / 竣工图生成资产 ID，现场扫码即可打开历史记录。
3. **让智能体输出可审计动作**：保留证据、阈值、责任人、工单和复测结果，支持验收和复盘。
4. **采用开放接入路线**：优先适配 Modbus TCP、MQTT、REST，并为 EPMS、SCADA、BMS 留出接口。

### 90 天落地路线

1. **0—2 周：资产建模**。完成回路、区段、测点编码与现场资料对齐。
2. **3—5 周：感知接入**。接入温度、电气量、网关和通信协议。
3. **6—9 周：智能分析**。校准阈值、趋势、根因模型和健康分。
4. **10—12 周：闭环验收**。完成工单联动、演练、培训和交付复盘。

### 适用场景

- 工业厂房的垂直母线与生产线分支
- 数据中心的机房母线与 UPS 末端
- 新能源、储能和关键基础设施的高可靠配电
- 既有母线改造与持续运维项目

### 参考资料

- [Siemens SIVACON](https://www.siemens.com/global/en/products/energy/low-voltage/systems/sivacon.html)
- [Schneider Electric 低压母线热监测](https://product-help.schneider-electric.com/EcoStruxure/Power-Monitoring-Expert-2024/content/applications/thermal_monitoring_-_lv_busway/operation/lvbw-operation.htm)
- [Eaton XAP Busway](https://www.eaton.com/au/en-gb/catalog/low-voltage-power-distribution-controls-systems/xap-series-busway.html)
- [Eaton XAPTrack 监测资料](https://www.eaton.com/content/dam/eaton/products/low-voltage-power-distribution-controls-systems/eatonbusbar/xap-track/xap-track-busway.pdf)

> 说明：横向对比用于产品设计和项目沟通，具体参数、认证、协议与交付边界以实际选型和合同为准。

