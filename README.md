## 在线视频播放相关知识

### 1、文件切割命令
```
```

### 2、ts文件合并命令
```
ffmpeg -i "concat:out000.ts|out002.ts|out003.ts" -acodec copy -vcodec copy -absf aac_adtstoasc out.mp4
```
```
ffmpeg -i "concat:out000.ts|out002.ts|out003.ts" -c copy -absf aac_adtstoasc  output.mp4
```
```
ffmpeg -i "concat:out000.ts|out002.ts|out003.ts" -c copy output.ts
```
```
import os
os.system("ffmpeg -i \"concat:out000.ts|out002.ts|out003.ts\" -c copy output.ts")
os.listdir("/Users/username/Downloads/tensorflow/download/20181007_213500")
```
```
ffmpeg -i "concat:output1.ts|output2.ts|output3.ts|output4.ts|output5.ts|output6.ts|output7.ts|output8.ts|output9.ts" -c copy output.ts
```