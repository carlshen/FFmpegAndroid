# 前言
FFmpeg是一个跨平台的多媒体库，也是目前音视频领域应用最广泛的库。包括libavcodec、libavformat、libavutil、</br>
libavdevice、libavfilter、libswscale、libswresample、libpostproc等模块。其中avcodec用于编解码，</br>
avformat用于解封装，avutil是提供工具类，avdevice用于各平台的设备接入，avfilter提供滤镜操作，</br>
swscale提供图像缩放与像素格式转换，swresample提供音频重采样，postproc提供高级处理。</br>
在这里，按照每个模块功能进行分析，如有错漏不当之处，敬请指出。</br>

### 1：AVIOContext、IO模型与协议
[AVIOContext结构体](https://blog.csdn.net/u011686167/article/details/121452343)

### 2：AVFormatContext连接FFmpeg的桥梁
[AVFormatContext](https://blog.csdn.net/u011686167/article/details/121483584)

### 3：AVCodecContext编解码器上下文
[AVCodecContext](https://blog.csdn.net/u011686167/article/details/121506335)

### 4：AVStream码流
[码流数组](https://blog.csdn.net/u011686167/article/details/121528354)

### 5：AVFrame与AVPacket
[AVFrame与AVPacket](https://blog.csdn.net/u011686167/article/details/121551041)

### 6：avformat_open_input()打开媒体流
[打开媒体流](https://blog.csdn.net/u011686167/article/details/121578185)

### 7：avformat_find_stream_info分析码流信息
[分析码流信息](https://blog.csdn.net/u011686167/article/details/121630969)

### 8：av_read_frame()读取音视频帧
[读取音视频帧](https://blog.csdn.net/u011686167/article/details/121642861)

### 9：av_parser_parse2()解析数据包
[解析数据包](https://blog.csdn.net/u011686167/article/details/121667755)

### 10：av_register_all()注册封装器与解封装器
[注册封装器与解封装器](https://blog.csdn.net/u011686167/article/details/121691245)