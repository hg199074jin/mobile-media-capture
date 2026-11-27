# 兼容性与保护机制

## 区分三类机制

| 机制 | 作用 | 可能表现 |
| --- | --- | --- |
| 截图/安全显示策略 | 约束画面捕获及外部显示 | 黑屏、禁止截图或投屏 |
| Android AudioPlaybackCapture 策略 | 约束其他应用或系统内部采集音频 | 软件录音无声或被拒绝 |
| HDCP | 保护数字音视频链路 | 普通采集卡无法接收受保护信号 |

音频输出、内部录音、视频输出和视频录制是不同能力；不应从正常播放推导出可采集性或录制权限。UCA222 是普通音频接口，不负责解密。

深造播放器的具体政策、手机型号、已购设备与课程许可尚未获得证据。不能承诺其音视频采集成功率。应询问平台是否提供官方电脑播放、讲义、音频/视频授权导出或转写许可。若存在禁止采集的限制，停止该路线。

## 官方参考

- [Android 音视频采集 API](https://developer.android.com/media/platform/av-capture)
- [Android AudioManager](https://developer.android.com/reference/android/media/AudioManager)
- [Elgato HDCP 限制](https://help.elgato.com/hc/en-us/articles/360040482032-HDCP-and-Elgato-Capture-devices)
- [Behringer UCA222](https://behringer.com/en/products/0805-AAG)

截至 2026-11-27，上述资料支持一般机制，不构成对具体播放器的实测结论。
