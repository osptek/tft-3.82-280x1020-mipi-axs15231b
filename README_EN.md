# 3.82" 280×1020 TFT MIPI module (AXS15231B) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 3.82-inch **TFT** panel, **280×1020** resolution |
| Interface | **MIPI** |
| Driver IC | **AXS15231B** |
| Spec ID | **`3.82-tft-280x1020-mipi-axs15231b`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization documentation |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (esp-lvgl-port + LVGL9) |

### Sample project paths

| Description | Path |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/P4-IDF_AXS15231B-MIPI_ESP-LVGL-PORT_V9/` |
