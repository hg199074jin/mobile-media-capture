# 视频传输与采集

实时显示不等于有权保存视频。优先使用平台官方电脑客户端、官方投屏或授权导出。

普通视频的硬件路径：支持视频输出的手机 → 兼容 USB-C 转 HDMI 转接器 → HDMI 线 → macOS 兼容 UVC HDMI 采集卡 → USB → OBS Studio。仅用于自有或明确允许采集的正常视频信号。

手机具有 USB-C 接口不代表支持 DisplayPort Alt Mode；Mac mini 自带 HDMI 是输出口。采集卡应核验 macOS 兼容性、实际采集分辨率、帧率、HDMI 音频支持和 USB 带宽。1080p30 是一般课件的建议起点，1080p60 按需求。对正常 HDMI 信号，兼容采集卡通常可以接收音视频；OBS 先录 MKV 后按需封装 MP4。若有独立音频源，验收音画同步。

HDCP 或安全显示策略可能导致黑屏、无信号或无法录制。不移除保护，不寻找规避方法；改用官方授权渠道。未确认手机型号和授权前不购买采集卡。

后续可对获准保存的视频独立研究课件关键帧、OCR 与时间轴；不属于本期已实现功能。

参考：[OBS 视频采集源](https://obsproject.com/kb/video-capture-sources)；[Elgato HDCP 限制](https://help.elgato.com/hc/en-us/articles/360040482032-HDCP-and-Elgato-Capture-devices)。
