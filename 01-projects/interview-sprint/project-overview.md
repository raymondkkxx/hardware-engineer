# 项目：高频面试突击与防御

> **目标**：用最短时间覆盖 80% 的硬件面试高频问题，确保“基础不送分、项目扛得住拷打”。

## 1. 硬件面试的真实结构
一场典型的硬件工程师技术面（45~60 分钟）通常只有三块：
1. **项目深挖（50%~60%）**：挑你简历上最亮眼的项目，从芯片选型、外围电路参数计算、PCB 布局一直问到现场 Debug 经历。
2. **硬核基础（30%）**：模电（运放、三极管/MOSFET）、电源（LDO/Buck）、数电与总线（I2C/SPI/UART/CAN）、无源器件（电容/电感/磁珠）。
3. **开放故障排查（10%~20%）**：比如“刚回来的新板子上电没反应 / 电源芯片发烫 / 通信偶尔丢包，你怎么查？”

## 2. 突击弹药库
- **速查清单**：[[03-resources/references/hardware-interview-checklist]]
- **面试官出题套路**：[[06-wiki/analyses/interview-question-patterns]]
- **模拟拷打指令**：[[05-skills/commands/mock-grill]]
- **面后极速复盘模板**：[[03-resources/templates/interview-retrospective-template]]

## 3. 个人薄弱点记录（随时随手记）
- `例：Buck 电感感值计算和饱和电流选型容易卡壳 -> 待看 [[06-wiki/concepts/power-integrity-and-decoupling]]`
