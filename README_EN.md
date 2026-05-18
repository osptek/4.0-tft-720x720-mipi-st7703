# 4.0" 720×720 TFT MIPI module (ST7703) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 4.0-inch **TFT** panel, **720×720** resolution |
| Interface | **MIPI** |
| Driver IC | **ST7703** |
| Spec ID | **`4.0-tft-720x720-mipi-st7703`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization notes, adapter documentation |
| `examples/` | **Sample projects** by category |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (esp-lvgl-port, GT911 touch, **LVGL游戏代码**, etc.) |
| `with-te/` | **屏幕防撕裂代码** |
| `eaf/` | **EAF动画代码** |
| `jpg-decoder/` | **jpeg解码** |
| `mjpeg/` | **mjpeg代码** |
| `camera/` | **摄像头代码** |
| `display-touch-test/` | **显示单独测试程序** |
| `arduino/` | **arduino代码** |

### Sample project paths

#### Baseline (`examples/` root)

| Description | Path |
|:--|:--|
| esp-lvgl-port + LVGL8 | `examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/` |
| esp-lvgl-port + LVGL9 | `examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/` |
| GT911 touch + LVGL8 | `examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/` |
| LVGL8 game demo (PVZ) | `examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/` |

#### Tear avoidance (`with-te/`)

| Description | Path |
|:--|:--|
| LVGL common demo | `examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/` |

#### EAF animation (`eaf/`)

| Description | Path |
|:--|:--|
| EAF player | `examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/` |

#### JPEG decode (`jpg-decoder/`)

| Description | Path |
|:--|:--|
| JPEG decode | `examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/` |
| JPEG decode + LVGL9 | `examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/` |

#### MJPEG (`mjpeg/`)

| Description | Path |
|:--|:--|
| MJPEG decode | `examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/` |
| MJPEG decode + LVGL9 | `examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/` |

#### Camera (`camera/`)

| Description | Path |
|:--|:--|
| Camera video on LCD | `examples/camera/p4-idf_st7703-mipi_video-lcd-display/` |

#### Display test (`display-touch-test/`)

| Description | Path |
|:--|:--|
| ST7703 MIPI DSI display test | `examples/display-touch-test/st7703_mipi_dsi/` |

#### Arduino (`arduino/`)

| Description | Path |
|:--|:--|
| Arduino + LVGL | `examples/arduino/esp32p4-arduino_st7703_lvgl/` |
| Arduino MJPEG decode | `examples/arduino/esp32p4_arduino_mjpeg-decode/` |
| SDMMC + ES8311 I2S | `examples/arduino/esp32p4_sdmmc_es8311-i2s/` |
