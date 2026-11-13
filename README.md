# Hardware Engineer Job-Hunting Second Brain (硬件工程师高效求职知识库)

> **目标**：用最短时间、最高 ROI 拿下满意的**硬件工程师** Offer。  
> **核心原则**：**结果导向、极度自由、支持激进想法、拒绝说教与时间表绑架**。

---

## 🧭 本库的使用哲学

1. **没有强制日程**：这里没有“每天几点该干嘛”的死板计划表，你随时按自己的状态和直觉决定先攻克什么。
2. **激进想法优先**：无论是“跳过枯燥基础直接画一块复杂板子”、“逆向拆解竞品抄板改版”、“直接给目标团队负责人发硬核技术邮件”，还是任何非常规打法——本库和 AI 助手只负责帮你**评估可行性、算清代价、找到最快落地方案**，绝不泼冷水、绝不居高临下当老师。
3. **以面试和交付为核心**：所有学习最终只服务于三件事——**简历能过筛、项目能扛住深挖、现场能解决硬件问题**。

---

## 🗂️ 目录架构 (PARA + Wiki 混合架构)

### 0. `_context/` —— 个人底盘与 AI 协作边界
- [[_context/personal-profile]]：个人背景、目标岗位方向、技能盘点（按需填写）
- [[_context/job-hunt-strategy]]：模块化求职打法菜单（简历/项目/面试/投递，随取随用）
- [[_context/ai-collaboration-rules]]：AI 协作铁律（不限制、不规定时间段、不强迫、支持激进方案）

### 1. `00-inbox/` —— 灵感、激进想法与面试碎片暂存
- [[00-inbox/daily/2026-11-14]]：今日随手记 / 激进点子 / 面试碎碎念
- [[00-inbox/_staging/staging-guide]]：草稿暂存与随手丢资料规范

### 2. `01-projects/` —— 结果驱动的求职攻坚项目
- [[01-projects/resume-and-portfolio/project-overview]]：简历打磨与作品集包装（用实测数据和波形说话）
- [[01-projects/interview-sprint/project-overview]]：高频面试突击与项目深挖防御
- [[01-projects/target-companies-tracker/companies-and-jd-matrix]]：目标公司、JD 拆解与投递追踪表
- [[01-projects/hardware-demo-project/project-overview]]：高含金量硬件 Demo 速成项目（缺硬核项目时用）

### 3. `02-areas/` —— 硬件工程师四大常驻能力域
- [[02-areas/analog-and-power/area-index]]：模电与电源设计（运放、MOSFET、LDO/DC-DC、保护电路）
- [[02-areas/digital-and-mcu/area-index]]：数电、MCU 最小系统与通信总线（SPI/I2C/UART/CAN/USB）
- [[02-areas/pcb-and-si-pi/area-index]]：PCB Layout、SI/PI 与 EMC/EMI 实战
- [[02-areas/lab-and-debugging/area-index]]：仪器仪表与硬件 Bring-up / Debug 排障

### 4. `03-resources/` —— 复盘模板与高频速查表
- [[03-resources/templates/radical-idea-sandbox-template]]：激进想法快速验证沙盒模板
- [[03-resources/templates/project-deep-dive-template]]：简历项目“防拷打”深挖模板
- [[03-resources/templates/interview-retrospective-template]]：面试极速复盘模板
- [[03-resources/references/hardware-interview-checklist]]：硬件面试高频考点速查清单

### 5. `04-archives/` —— 阶段归档
- [[04-archives/archive-index]]：已投完的批次、旧版简历、已拿 Offer 的复盘归档

### 6. `05-skills/` —— AI 协作指令集（按需召唤）
- [[05-skills/commands/pitch-idea]]：用激进/非常规想法直接推演最快落地方案
- [[05-skills/commands/mock-grill]]：模拟硬核硬件面试官拷打你的项目细节
- [[05-skills/commands/jd-hack]]：拆解目标 JD，提取最高 ROI 突击点
- [[05-skills/commands/debug-circuit]]：硬件调板/排障定位助手
- [[05-skills/commands/review-resume]]：用招聘方视角犀利优化简历

### 7. `06-wiki/` —— 沉淀后的硬件工程与面试底层百科
- **总索引**：[[06-wiki/wiki-index]]
- **核心概念 (`concepts/`)**：
  - [[06-wiki/concepts/power-integrity-and-decoupling]]：去耦电容、PDN 与 LDO/DC-DC 实战权衡
  - [[06-wiki/concepts/emc-esd-and-grounding]]：接地、回流路径、ESD 防护与 EMC 整改套路
  - [[06-wiki/concepts/bus-protocols-pitfalls]]：I2C/SPI/UART/CAN 常见硬件坑与计算
- **器件实体 (`entities/`)**：
  - [[06-wiki/entities/common-components-cheatsheet]]：MOSFET、运放、晶振、MLCC、TVS 选型避坑
- **深度剖析 (`analyses/`) & 资料源 (`sources/`)**：
  - [[06-wiki/analyses/interview-question-patterns]]：硬件面试官出题逻辑与高频追问链
  - [[06-wiki/sources/datasheets-and-app-notes]]：高价值芯片手册、参考设计与工具清单
