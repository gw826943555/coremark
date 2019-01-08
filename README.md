# hello

## 1、介绍

CoreMark 是一项测试处理器性能的基准测试。本软件包是CoreMark基于RT—Thread的移植，源码来自于[eembc](https://github.com/eembc/coremark)。

### 1.1 目录结构

| 名称 | 说明 |
| ---- | ---- |
| docs  | 文档目录 |
| examples | 例子目录，并有相应的一些说明 |
| inc  | 头文件目录 |
| src  | 源代码目录 |

### 1.2 许可证

coremark package 遵循 Apache License 2.0 许可，详见 `LICENSE` 文件。

### 1.3 依赖

- RT-Thread 4.0+

## 2、如何打开 coremark

使用 hello package 需要在 RT-Thread 的包管理器中选择它，具体路径如下：

```
RT-Thread online packages
    miscellaneous packages --->
        [*] A coremark package
```

然后让 RT-Thread 的包管理器自动更新，或者使用 `pkgs --update` 命令更新包到 BSP 中。

## 3、使用 hello

在打开 hello package 后，当进行 bsp 编译时，它会被加入到 bsp 工程中进行编译。

* 打开控制台，输入 `coremark n`，其中n为测试进行的迭代次数，省略时默认为1000。
* 根据芯片性能，运行时间存在差异，请耐心等待，推荐测试时间10秒以上。 

## 4、注意事项

编译器和优化等级对测试结果有较大影响，测试结果仅供参考。

## 5、联系方式 & 感谢

* 维护：William
* 主页：https://github.com/gw826943555/coremark
