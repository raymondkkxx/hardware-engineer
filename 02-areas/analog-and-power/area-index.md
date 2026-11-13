# 能力域：模电与电源设计 (Analog & Power)

> **定位**：硬件工程师面试淘汰率最高的核心域。不背教科书，只聚焦工程选型、核心计算与常见翻车点。

## 核心知识地图
1. **无源器件真实特性**
   - MLCC 电容的直流偏压（DC Bias）效应、ESR/ESL 与谐振频率
   - 电感的饱和电流 $I_{sat}$ 与温升电流 $I_{rms}$
   - 磁珠 vs 电阻 vs 电感在滤波中的选型边界
   - 详见：[[06-wiki/entities/common-components-cheatsheet]]
2. **晶体管与开关电路**
   - BJT 三极管饱和/放大判断、基极驱动电阻计算
   - MOSFET 核心参数：$V_{GS(th)}$、$R_{DS(on)}$、米勒平台与 $Q_g$、开关损耗 vs 导通损耗
   - 防反接电路（PMOS vs NMOS vs 肖特基二极管）与高边/低边驱动
3. **运算放大器实战**
   - 虚短虚断应用（同相/反相/差分/仪表放大器/跨阻放大器 TIA）
   - 压摆率（Slew Rate）、增益带宽积（GBW）、轨到轨（Rail-to-Rail）、输入失调电压
   - 容性负载导致运放自激振荡的消振方法
4. **电源拓扑与电源树**
   - LDO vs Buck vs Boost 权衡（压差、效率、纹波、PSRR、散热）
   - Buck 电感与输出电容计算、Bootstrap 自举电容作用、SW 节点振铃抑制（RC Snubber / 栅极电阻）
   - 详见：[[06-wiki/concepts/power-integrity-and-decoupling]]
