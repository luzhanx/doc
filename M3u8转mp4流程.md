# M3u8转mp4流程

### 先下载[ffmpeg](https://ffmpeg.zeranoe.com/builds/) 解压出来
```
1. 用cmd 进入到解压出来文件夹路径 在进入bin目录 
2. 执行下面这段cmd命令转换成mp4 等待转换完成即可 
   其中 http://xxxxxx/video/movie.m3u8 视频的m3u8地址, output.mp4 为输出mp4的文件名

    ffmpeg  -i "http://xxxxxx/video/movie.m3u8" -vcodec copy -acodec copy -absf aac_adtstoasc  output.mp4
    
```
