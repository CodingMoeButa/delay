# delay
为解决 Windows Batch 之 TIMEOUT 命令不支持毫秒级参数而编写之替代方案。

## 使用方法
将编译完成的`delay.exe`文件置于主执行程序相同文件夹下，使用以下 Batch 命令调用：
```batch
delay <毫秒数>
```

## 示例
延迟一秒：
```batch
delay 1000
```

## Linux
Linux 下的 shell 命令`sleep`似乎也不接受毫秒型参数，可将本程序源代码置于 Linux 下编译使用。
