# 工商业储能、锂电储能与欧盟新电池法案 (EU Battery Passport) 技术规约

## 1. 行业覆盖与典型客户站点
- `sossenergy.com` (索森能源 - 工商业储能柜 BESS、户用光储一体机、户外便携电源)

## 2. 国际认证与安全准入标准
- **北美准入**：UL 9540 (储能系统和设备)、UL 9540A (大规模热失控蔓延测试)、UL 1973 (固定式电池系统安全)、NFPA 855 (固定式储能系统安装防火防爆规范)。
- **欧洲准入**：IEC 62619 (工业用二次锂电池安全要求)、IEC 62477-1 (电力电子系统安全)、CE EMC & LVD、VDE-AR-N 4105 / EN 50549 (并网逆变合规)。
- **运输与航运认证**：UN 38.3 锂电池运输测试、MSDS 化学品安全技术说明书。

## 3. 欧盟新电池法案 (EU Battery Regulation 2023/1542 & Battery Passport)
自 2026/2027 年起，所有进入欧盟市场容量超过 $2\text{ kWh}$ 的工业及储能电池强制要求拥有数字电池护照 (Digital Battery Passport)：
- **碳足迹声明 (Carbon Footprint Declaration)**：从原材料提炼、电芯制造到模块组装的全生命周期 $\text{kg CO}_2\text{e/kWh}$。
- **再生原材料回收比例 (Recycled Content)**：强制披露钴 (Co)、锂 (Li)、镍 (Ni) 的回收材料占比。
- **电池健康度与预期寿命 (State of Health - SOH)**：额定容量、循环寿命 ($\ge 6000\text{ 次 @ 80% DOD}$)、日历寿命 ($\ge 15\text{ 年}$)。
- **静态预渲染着陆页**：每个储能型号必须静态生成独立着陆页（`/dpp-bess-{model}`），并在 `sitemap-dpp.xml` 中广播。
