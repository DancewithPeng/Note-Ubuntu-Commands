# Blog-Ubuntu-Commands
Ubuntu常用命令
[curl](#curl - URL工具)
[netstat](#netstat - 查看网络状态)
[kill](#kill - 杀死进程)
[grep](#grep - 全局搜索工具)

## curl - URL工具
```
  curl [options...] <url>
```
常用的option有

  - `-o 将下载的数据保存到指定的文件`
  - `-i 同时显示HTTP Header`

## netstat - 查看网络状态
```
  netstat [options...]
```
常用的option有
  - `-r 显示路由表`
  - `-a 显示所有的socket`
  - `-p 显示PID和程序名称`
  
## kill - 杀死进程
```
  kill [signal] <PID>
```
常用的signal有
  - `-9 exit 退出进程`
  
## grep - 全局搜索工具
```
  <command> | grep [options...] <RE>
```
常见的option有

  - `-i 忽略大小写`

## cat - 查看文件内容
```
  cat [options...] <filename>
```
常见的option有

  - `-a 显示所有内容`
  - `-n 同时显示行号`
  
## tail - 查看文件最末尾的内容
```
  tail [options...] <filename>
```
常见的option有

  - `-n 显示最后几行的内容`
  - `-f 显示最后10行内容，并且有新内容增加的时候，自动显示新增的内容`
