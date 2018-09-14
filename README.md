# fetch-audio-from-fm
从FM网站批量下载某专辑的音频，并转换到MP3格式

现在支持的网站:
------
www.ximalaya.com  
www.qingting.fm  
www.lizhi.fm

注意:
------
除lizhi以外其他网站必须安装ffmpeg

使用方法:
------
ruby ximalaya http://www.ximalaya.com/11129614/album/2872220  
如果希望下载标题包含某个词(如:侯景传)的音频，可以使用:  
ruby ximalaya http://www.ximalaya.com/11129614/album/2872220 侯景传  
其他网站的下载方法都相同  

依赖:
------
https://github.com/YorickPeterse/oga  
https://github.com/rdp/os  

Notes:
------
ximalaya是[https://github.com/zhenze12345/ximalaya](https://github.com/zhenze12345/ximalaya)的多线程版本
