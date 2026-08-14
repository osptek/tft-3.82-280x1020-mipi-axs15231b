<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.82″ TFT 280×1020 (AXS15231B · MIPI)</h1>

<p align="center"><b>Bar TFT module · MIPI · AXS15231B · capacitive touch</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 3.82 inch" src="https://img.shields.io/badge/Size-3.82%22-3498DB?style=flat-square" />
  <img alt="Resolution: 280x1020" src="https://img.shields.io/badge/Resolution-280%C3%971020-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: AXS15231B" src="https://img.shields.io/badge/Driver-AXS15231B-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 3.82&quot; 280×1020 TFT MIPI module (AXS15231B) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **3.82″ 280×1020 TFT** is a **MIPI** color display module. Display and capacitive touch are both driven by **AXS15231B** (touch over I2C). Suited to bar-style HMI and narrow side panels.

Spec ID (repository name): `3.82-tft-280x1020-mipi-axs15231b`

Current module version: **YDP382B001-V13**. Electrical and mechanical details follow [`docs/YDP_382_B001_V13_9b4d899817.pdf`](./docs/YDP_382_B001_V13_9b4d899817.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 3.82 inch |
| Type | TFT (color) |
| Resolution | 280×1020 |
| Interface | MIPI |
| Driver IC | AXS15231B |
| Touch driver | AXS15231B |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-P4 · AXS15231B MIPI + esp-lvgl-port / LVGL9 | [`examples/P4-IDF_AXS15231B-MIPI_ESP-LVGL-PORT_V9/`](./examples/P4-IDF_AXS15231B-MIPI_ESP-LVGL-PORT_V9/) |

## Repository layout

```text
3.82-tft-280x1020-mipi-axs15231b/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP382B001-V13/                                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP382B001-V13) | [`docs/YDP_382_B001_V13_9b4d899817.pdf`](./docs/YDP_382_B001_V13_9b4d899817.pdf) |
| Driver IC datasheet (AXS15231B) | [`docs/AXS_15231_B_Datasheet_V0_9_20240221_5a76ce6ce2.pdf`](./docs/AXS_15231_B_Datasheet_V0_9_20240221_5a76ce6ce2.pdf) |
| Init sequence (text) | [`docs/YP008_Lint_231+信利3.82_V07.txt`](./docs/YP008_Lint_231%2B%E4%BF%A1%E5%88%A93.82_V07.txt) |

### Samples

- [ESP32-P4 AXS15231B MIPI + LVGL9](./examples/P4-IDF_AXS15231B-MIPI_ESP-LVGL-PORT_V9/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group: **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository with any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
