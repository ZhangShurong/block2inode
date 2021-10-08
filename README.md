# debugfs
## 使用方法
```
debugfs -i inputfile outputfile #inode转文件名
debugfs -b inputfile outputfile #block转文件名
```

## 输入文件格式
块号或者inode:挂载点:时间戳:读写:大小

##输出文件格式
块号或者inode:时间戳:读写:大小:文件名