<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 4.0″ TFT 720×720（ST7703 · MIPI）</h1>

<p align="center"><b>方形 TFT / IPS 模组 · MIPI · ST7703 · 电容触摸</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Size: 4.0 inch" src="https://img.shields.io/badge/Size-4.0%22-3498DB?style=flat-square" />
  <img alt="Resolution: 720x720" src="https://img.shields.io/badge/Resolution-720%C3%97720-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7703" src="https://img.shields.io/badge/Driver-ST7703-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 4.0 寸 720×720 TFT MIPI 模组（ST7703）宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [产品简介](#产品简介)
- [规格参数](#规格参数)
- [示例工程](#示例工程)
- [仓库结构](#仓库结构)
- [相关资料](#相关资料)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 产品简介

OSPTEK **4.0 寸 720×720 TFT（IPS）** 是一款 **MIPI** 接口彩色显示模组，显示驱动为 **ST7703**，触摸驱动为 **GT911**。适合方形 HMI、仪表与中尺寸交互面板等场景。

规格标识（仓库名）：`4.0-tft-720x720-mipi-st7703`

当前模组版本：**YDP400BT001-V4**。电气与外形细节以 [`docs/YDP_400_BT_001_V4_058148418c.pdf`](./docs/YDP_400_BT_001_V4_058148418c.pdf) 为准。

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 4.0 英寸 |
| 类型 | TFT / IPS（彩色） |
| 分辨率 | 720×720 |
| 接口 | MIPI |
| 驱动 IC | ST7703 |
| 触摸驱动 | GT911 |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 示例工程

| 说明 | 路径 |
| ---- | ---- |
| ESP32-P4 · ST7703 MIPI + esp-lvgl-port / LVGL8 | [`examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/`](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/) |
| ESP32-P4 · ST7703 MIPI + esp-lvgl-port / LVGL9 | [`examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/`](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/) |
| ESP32-P4 · ST7703 MIPI + GT911 + LVGL8 | [`examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/`](./examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/) |
| ESP32-P4 · LVGL8 游戏示例（PVZ） | [`examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/`](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/) |
| ESP32-P4 · LVGL + TE 防撕裂 | [`examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/`](./examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/) |
| ESP32-P4 · EAF 动画播放 | [`examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/`](./examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/) |
| ESP32-P4 · JPEG 解码 | [`examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/`](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/) |
| ESP32-P4 · JPEG 解码 + LVGL9 | [`examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/`](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/) |
| ESP32-P4 · MJPEG 解码 | [`examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/`](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/) |
| ESP32-P4 · MJPEG 解码 + LVGL9 | [`examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/`](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/) |
| ESP32-P4 · 摄像头视频 LCD 显示 | [`examples/camera/p4-idf_st7703-mipi_video-lcd-display/`](./examples/camera/p4-idf_st7703-mipi_video-lcd-display/) |
| ESP32-P4 · ST7703 MIPI DSI 显示测试 | [`examples/display-touch-test/st7703_mipi_dsi/`](./examples/display-touch-test/st7703_mipi_dsi/) |
| ESP32-P4 · Arduino + ST7703 + LVGL | [`examples/arduino/esp32p4-arduino_st7703_lvgl/`](./examples/arduino/esp32p4-arduino_st7703_lvgl/) |
| ESP32-P4 · Arduino MJPEG 解码 | [`examples/arduino/esp32p4_arduino_mjpeg-decode/`](./examples/arduino/esp32p4_arduino_mjpeg-decode/) |
| ESP32-P4 · Arduino SDMMC + ES8311 I2S | [`examples/arduino/esp32p4_sdmmc_es8311-i2s/`](./examples/arduino/esp32p4_sdmmc_es8311-i2s/) |

## 仓库结构

```text
4.0-tft-720x720-mipi-st7703/                                # 仓库根（导航见 ../../README.md）
└── versions/
    └── YDP400BT001-V4/                                # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## 相关资料

### 本产品资料

| 资料 | 链接 |
| ---- | ---- |
| 产品规格书（YDP400BT001-V4） | [`docs/YDP_400_BT_001_V4_058148418c.pdf`](./docs/YDP_400_BT_001_V4_058148418c.pdf) |
| 驱动 IC 数据手册（ST7703） | [`docs/ST7703DA-H3_DS_V0.01_20200819.pdf`](./docs/ST7703DA-H3_DS_V0.01_20200819.pdf) |
| 触摸 IC 数据手册（GT911） | [`docs/GT_911_Datasheet_20140718_Rev_08_daa11566d3.pdf`](./docs/GT_911_Datasheet_20140718_Rev_08_daa11566d3.pdf) |
| 初始化序列（文本） | [`docs/2-ST7703_QV040YNQ-N80_IPS_Code_2Power_V5.5_20230731.txt`](./docs/2-ST7703_QV040YNQ-N80_IPS_Code_2Power_V5.5_20230731.txt) |
| 初始化命令表（`st7703.h`） | [`docs/st7703.h`](./docs/st7703.h) |
| 2.1 / 4″ 转接板（P4） | [`docs/2.1&4“转接板SCRREN_P4_yuying.pdf`](./docs/2.1%264%E2%80%9C%E8%BD%AC%E6%8E%A5%E6%9D%BFSCRREN_P4_yuying.pdf) |

### 示例工程

- [ESP32-P4 ST7703 MIPI + LVGL8](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8/)
- [ESP32-P4 ST7703 MIPI + LVGL9](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V9/)
- [ESP32-P4 ST7703 MIPI + GT911 + LVGL8](./examples/P4-IDF_ST7703-MIPI_GT911-I2C_LVGL-V8/)
- [ESP32-P4 LVGL8 游戏示例（PVZ）](./examples/P4-IDF_ST7703-MIPI_ESP-LVGL-PORT_V8_PVZ/)
- [ESP32-P4 LVGL + TE](./examples/with-te/p4-idf_st7703-mipi_lvgl_common_demo/)
- [ESP32-P4 EAF 动画播放](./examples/eaf/p4-idf_st7703-mipi_esp-lv-eaf-player/)
- [ESP32-P4 JPEG 解码](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode/)
- [ESP32-P4 JPEG 解码 + LVGL9](./examples/jpg-decoder/p4-idf_st7703-mipi_jpeg-decode_lvgl-v9/)
- [ESP32-P4 MJPEG 解码](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode/)
- [ESP32-P4 MJPEG 解码 + LVGL9](./examples/mjpeg/p4-idf_st7703-mipi_mjpeg-decode_lvgl-v9/)
- [ESP32-P4 摄像头视频 LCD 显示](./examples/camera/p4-idf_st7703-mipi_video-lcd-display/)
- [ESP32-P4 ST7703 MIPI DSI 显示测试](./examples/display-touch-test/st7703_mipi_dsi/)
- [ESP32-P4 Arduino + ST7703 + LVGL](./examples/arduino/esp32p4-arduino_st7703_lvgl/)
- [ESP32-P4 Arduino MJPEG 解码](./examples/arduino/esp32p4_arduino_mjpeg-decode/)
- [ESP32-P4 Arduino SDMMC + ES8311 I2S](./examples/arduino/esp32p4_sdmmc_es8311-i2s/)

## 购买链接

<p align="center">
  <a href="https://shop110742373.taobao.com/"><img alt="淘宝官方店铺" src="https://img.shields.io/badge/淘宝-官方店铺-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="速卖通官方店铺" src="https://img.shields.io/badge/速卖通-官方店铺-FF6A00?style=for-the-badge" /></a>
</p>

**国内（淘宝）**

- 店铺：[鱼鹰光电工厂店](https://shop110742373.taobao.com/)

**海外（AliExpress）**

- 店铺：[OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

## 技术支持

- 技术支持 / 产品咨询：<luyu@osptek.com>
- QQ 技术交流群：**985881096**
- 公司官网：<https://osptek.com/>
- 有任何问题，都可以在本仓库 Issues 中提问

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
