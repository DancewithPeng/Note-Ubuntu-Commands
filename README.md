# Blog-Ubuntu-Commands
Ubuntu常用命令

## curl - URL工具
```
  curl [options...] <url>
```
常用的option有

  - `-o 将下载的数据保存到指定的文件`
  - `-i 只下载响应头`

## netstat - 查看网络状态
```
  netstat [options...]
```
常用的option有
  - `-r 显示路由表`
  - `-a 显示所有的socket`
  - `-p 显示PID和程序名称`
  
### kill - 杀死进程
---
```
  kill [signal] <PID>
```
常用的signal有
  - `-9 exit 退出进程`
  
### grep - 全局搜索工具
---
```
  command | grep [options...] <RE>
```
常见的option有

  - `-i 忽略大小写`
  
