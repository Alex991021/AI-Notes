## 一、vim

### 1.1 多行注释

- 多行注释：「Ctrl - v」选择要注释的行 -> 「Shift + i」-> 「输入注释字符」-> 「Esc」
- 删除多行注释：「Ctrl - v」选择要删除的注释字符 -> 「d」

### 1.2 查找替换

全局替换，每次确认，「y」 替换，「n」 下一个：

```
:%s/要替换/替换为/gc
```

### 1.3 vim 滚屏

1. Ctrl + F 屏幕向下滚动一屏
2. Ctrl + B 屏幕向上滚动一屏
3. Ctrl + E 屏幕向下滚动一行
4. Ctrl + Y 屏幕向上滚动一行
5. Ctrl + D 屏幕向下滚动半屏
6. Ctrl + U 屏幕向上滚动半屏

## 二、Shell

### 2.1 find 查找文件

```shell
# 在当前目录及其子目录下查找名为 xxx.xxx 的文件，可以使用正则化
find . -name "xxx.xxx"
```

### 2.2 查看系统 CPU 运行状态

使用 top 或者 htop 工具，后者更香：

```shell
top
```

```shell
sudo apt install htop
htop
```

