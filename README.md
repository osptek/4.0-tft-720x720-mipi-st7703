# 4.0 寸 720×720 TFT MIPI 模组（ST7703）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 4.0 英寸 **TFT**，分辨率 **720×720** |
| 接口 | **MIPI** |
| 驱动芯片 | **ST7703** |
| 规格标识 | 产品资料中常用 **`4.0-tft-720x720-mipi-st7703`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、初始化与转接板资料 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **ESP-IDF代码**（esp-lvgl-port、GT911 触摸、**LVGL游戏代码** 等） |
| `with-te/` | **屏幕防撕裂代码** |
| `eaf/` | **EAF动画代码** |
| `jpg-decoder/` | **jpeg解码** |
| `mjpeg/` | **mjpeg代码** |
| `camera/` | **摄像头代码** |
| `display-touch-test/` | **显示单独测试程序** |
| `arduino/` | **arduino代码** |

### 示例工程路径

#### 基础（`examples/` 根目录）

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-port + LVGL8 | `examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/` |
| esp-lvgl-port + LVGL9 | `examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/` |
| GT911 触摸 + LVGL8 | `examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/` |
| LVGL8 游戏示例（PVZ） | `examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| LVGL 通用演示 | `examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/` |

#### EAF动画代码（`eaf/`）

| 说明 | 路径 |
|:--|:--|
| EAF 动画播放 | `examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/` |

#### jpeg解码（`jpg-decoder/`）

| 说明 | 路径 |
|:--|:--|
| JPEG 解码 | `examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/` |
| JPEG 解码 + LVGL9 | `examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/` |

#### mjpeg代码（`mjpeg/`）

| 说明 | 路径 |
|:--|:--|
| MJPEG 解码 | `examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/` |
| MJPEG 解码 + LVGL9 | `examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/` |

#### 摄像头代码（`camera/`）

| 说明 | 路径 |
|:--|:--|
| 摄像头视频 LCD 显示 | `examples/camera/p4-idf_st7703-mipi_video-lcd-display/` |

#### 显示单独测试程序（`display-touch-test/`）

| 说明 | 路径 |
|:--|:--|
| ST7703 MIPI DSI 显示测试 | `examples/display-touch-test/st7703_mipi_dsi/` |

#### arduino代码（`arduino/`）

| 说明 | 路径 |
|:--|:--|
| Arduino + LVGL | `examples/arduino/esp32p4-arduino_st7703_lvgl/` |
| Arduino MJPEG 解码 | `examples/arduino/esp32p4_arduino_mjpeg-decode/` |
| SDMMC + ES8311 I2S | `examples/arduino/esp32p4_sdmmc_es8311-i2s/` |
