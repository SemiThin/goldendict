# GoldenDict 完美样式 

### GoldenDict
[GoldenDict](http://goldendict.org/) 是一款不错的、与StarDict（星际译王）类似的词典软件。它使用 WebKit作为渲染核心，格式化、颜色、图像、链接等支持一应俱全；支持多种词典文件格式，包括Babylon的 .BGL 文件、StarDict 的 .ifo/.dict/.idx/.syn 文件、Dictd的·index/.dict(.dz) 文件、ABBYY Lingvo 的 .dsl/.lsa/.dat 文件。

### 使用方法
```
# 生成二进制文件
go build .
```

```azure
# GoldenDict->编辑->词典->程序->添加(类型选择HTML，命令行为： 二进制文件路径 %GDWORD%)
/home/ubuntu/goldendict/youdao %GDWORD%
```

### 感谢leo,goland代码转自以下python
https://github.com/easeflyer/gd_plugin
