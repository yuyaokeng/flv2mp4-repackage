# 一个调用ffmpeg批量将视频重封装入`.mp4`格式容器的脚本
食用方法：将`flv2mp4.py`和视频放在同一目录下，运行。

ps:
- 写这个东西是因为从视频网站上下载的很多视频（如BILIBILI)为`.flv`，但容器内视频流实际上是H264，完全可以封装成`.mp4`，且在手机上flv不能硬解，而mp4能。
- 只进行了重封装，没有进行转码。因为完全没有必要，即费时又损清晰度。
- 因为上一条，原视频格式容器内的视频流必须是H264、MPEG4或其他`.mp4`支持的编码