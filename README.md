# fetch-audio-from-fm
从FM网站如获取音频，并转换到MP3格式

现在支持的网站:
------
www.ximalya.com  
www.qingting.fm  
www.kaolafm.com  

注意:
------
除kaolafm以外其他网站必须安装ffmpeg

使用方法:
------
ruby ximalya http://www.ximalaya.com/11129614/album/2872220  
如果希望下载标题包含某个词(如:侯景传)的音频，可以使用:  
ruby ximalaya http://www.ximalaya.com/11129614/album/2872220 侯景传

依赖:
------
[oga](https://github.com/YorickPeterse/oga "oga")

Notes:
------
ximalya是https://github.com/zhenze12345/ximalaya的多线程版本
