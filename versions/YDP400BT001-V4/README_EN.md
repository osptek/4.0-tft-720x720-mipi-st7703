<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 4.0″ TFT 720×720 (ST7703 · MIPI)</h1>

<p align="center"><b>Square TFT / IPS module · MIPI · ST7703 · capacitive touch</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 4.0 inch" src="https://img.shields.io/badge/Size-4.0%22-3498DB?style=flat-square" />
  <img alt="Resolution: 720x720" src="https://img.shields.io/badge/Resolution-720%C3%97720-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7703" src="https://img.shields.io/badge/Driver-ST7703-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 4.0″ 720×720 TFT MIPI module (ST7703) product image" src="./images/product.png" width="640" /></p>

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

OSPTEK **4.0″ 720×720 TFT (IPS)** is a **MIPI** color display module driven by **ST7703**, with capacitive touch (**GT911**). Suited to square HMI, instruments, and mid-size interactive panels.

Spec ID (repository name): `4.0-tft-720x720-mipi-st7703`

Current module version: **YDP400BT001-V4**. Electrical and mechanical details follow [`docs/YDP_400_BT_001_V4_058148418c.pdf`](./docs/YDP_400_BT_001_V4_058148418c.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 4.0 inch |
| Type | TFT / IPS (color) |
| Resolution | 720×720 |
| Interface | MIPI |
| Driver IC | ST7703 |
| Touch driver | GT911 |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-P4 · ST7703 MIPI + esp-lvgl-port / LVGL8 | [`examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/`](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/) |
| ESP32-P4 · ST7703 MIPI + esp-lvgl-port / LVGL9 | [`examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/`](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/) |
| ESP32-P4 · ST7703 MIPI + GT911 + LVGL8 | [`examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/`](./examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/) |
| ESP32-P4 · LVGL8 game sample (PVZ) | [`examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/`](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/) |
| ESP32-P4 · LVGL + TE | [`examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/`](./examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/) |
| ESP32-P4 · EAF animation player | [`examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/`](./examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/) |
| ESP32-P4 · JPEG decode | [`examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/`](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/) |
| ESP32-P4 · JPEG decode + LVGL9 | [`examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/`](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/) |
| ESP32-P4 · MJPEG decode | [`examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/`](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/) |
| ESP32-P4 · MJPEG decode + LVGL9 | [`examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/`](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/) |
| ESP32-P4 · camera video to LCD | [`examples/camera/p4-idf_st7703-mipi_video-lcd-display/`](./examples/camera/p4-idf_st7703-mipi_video-lcd-display/) |
| ESP32-P4 · ST7703 MIPI DSI display test | [`examples/display-touch-test/st7703_mipi_dsi/`](./examples/display-touch-test/st7703_mipi_dsi/) |
| ESP32-P4 · Arduino + ST7703 + LVGL | [`examples/arduino/esp32p4-arduino_st7703_lvgl/`](./examples/arduino/esp32p4-arduino_st7703_lvgl/) |
| ESP32-P4 · Arduino MJPEG decode | [`examples/arduino/esp32p4_arduino_mjpeg-decode/`](./examples/arduino/esp32p4_arduino_mjpeg-decode/) |
| ESP32-P4 · Arduino SDMMC + ES8311 I2S | [`examples/arduino/esp32p4_sdmmc_es8311-i2s/`](./examples/arduino/esp32p4_sdmmc_es8311-i2s/) |

## Repository layout

```text
4.0-tft-720x720-mipi-st7703/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP400BT001-V4/                                # full materials for this part number
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
| Product datasheet (YDP400BT001-V4) | [`docs/YDP_400_BT_001_V4_058148418c.pdf`](./docs/YDP_400_BT_001_V4_058148418c.pdf) |
| Driver IC datasheet (ST7703) | [`docs/ST7703DA-H3_DS_V0.01_20200819.pdf`](./docs/ST7703DA-H3_DS_V0.01_20200819.pdf) |
| Touch IC datasheet (GT911) | [`docs/GT_911_Datasheet_20140718_Rev_08_daa11566d3.pdf`](./docs/GT_911_Datasheet_20140718_Rev_08_daa11566d3.pdf) |
| Init sequence (text) | [`docs/2-ST7703_QV040YNQ-N80_IPS_Code_2Power_V5.5_20230731.txt`](./docs/2-ST7703_QV040YNQ-N80_IPS_Code_2Power_V5.5_20230731.txt) |
| Init command table (`st7703.h`) | [`docs/st7703.h`](./docs/st7703.h) |
| 2.1 / 4″ adapter board (P4) | [`docs/2.1&4“转接板SCRREN_P4_yuying.pdf`](./docs/2.1%264%E2%80%9C%E8%BD%AC%E6%8E%A5%E6%9D%BFSCRREN_P4_yuying.pdf) |

### Samples

- [ESP32-P4 ST7703 MIPI + LVGL8](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/)
- [ESP32-P4 ST7703 MIPI + LVGL9](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/)
- [ESP32-P4 ST7703 MIPI + GT911 + LVGL8](./examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/)
- [ESP32-P4 LVGL8 game sample (PVZ)](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/)
- [ESP32-P4 LVGL + TE](./examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/)
- [ESP32-P4 EAF animation player](./examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/)
- [ESP32-P4 JPEG decode](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/)
- [ESP32-P4 JPEG decode + LVGL9](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/)
- [ESP32-P4 MJPEG decode](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/)
- [ESP32-P4 MJPEG decode + LVGL9](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/)
- [ESP32-P4 camera video to LCD](./examples/camera/p4-idf_st7703-mipi_video-lcd-display/)
- [ESP32-P4 ST7703 MIPI DSI display test](./examples/display-touch-test/st7703_mipi_dsi/)
- [ESP32-P4 Arduino + ST7703 + LVGL](./examples/arduino/esp32p4-arduino_st7703_lvgl/)
- [ESP32-P4 Arduino MJPEG decode](./examples/arduino/esp32p4_arduino_mjpeg-decode/)
- [ESP32-P4 Arduino SDMMC + ES8311 I2S](./examples/arduino/esp32p4_sdmmc_es8311-i2s/)

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
