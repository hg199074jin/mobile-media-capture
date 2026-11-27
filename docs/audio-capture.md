# 音频采集方案

## 目的与边界

将允许录制的普通手机音频以标准文件保存到电脑，便于后续个人学习和转写。对明确禁止录制的课程，使用官方许可途径，不以外接设备规避限制。

## 硬件

历史讨论选型：绿联 USB-C 转 3.5 mm 有源 DAC、雷克森 3.5 mm TRS 转双 RCA 公头音频线、Behringer UCA222 USB 声卡（UCA202 备选，需核验）。UCA222 提供立体声 RCA 线级输入，不支持视频。手机与 DAC 兼容性待核验。

## 普通音频连接

仅用于自有或获准录制的正常音频：手机正常音频输出 → DAC → 3.5 mm/RCA 音频线 → UCA222 RCA INPUT L/R → USB → 电脑。Mac 若缺 USB-A 口，使用兼容的 USB 数据转接器。

Audacity 在 macOS 上使用 Core Audio；Windows 可用 MME。选择实际识别的声卡输入，建议立体声、48 kHz、16-bit PCM WAV。先用自有音频试录，检查声道、音量、失真和底噪，避免削波。结束采集后导出 WAV，保持原件完整。

## 加密播放器

Android 软件内部音频采集受应用策略约束；HDCP 是数字音视频链路保护。UCA222 不是解密设备。正常音频输出与录制许可均需确认，不能据此保证特定播放器可被录制。若播放器或授权明确限制录制，停止并向平台申请许可。参见[兼容性](compatibility.md)。

## 参考

- [UCA222 官方产品说明](https://behringer.com/en/products/0805-AAG)
- [Audacity 官网](https://www.audacityteam.org/)
