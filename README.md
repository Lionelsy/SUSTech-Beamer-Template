# SUSTech-Beamer-Template
A SUSTech beamer template. (Support Chinese).



主要根据THU的翁家翌前辈的[Beamer模版](https://github.com/Trinkle23897/THU-Beamer-Theme)修改，

色彩主题参考了官方[Beamer模版](https://github.com/SUSTC/sustech-slides)配色。



## 特性

### 顶部重叠显示目录

对比🆚效果：

- 此模版
  - ![P1](./figs/P1.png)

- 官方
  - ![P2](/Users/zhangshu/Documents/github/SUSTech-Beamer-Template/figs/P2.png)



### 支持中文显示

(虽然好像直接ctex或者utf8就行。。。)



## [效果预览](./slide.pdf) 

![P3](/Users/zhangshu/Documents/github/SUSTech-Beamer-Template/figs/P3.png)



![P4](/Users/zhangshu/Documents/github/SUSTech-Beamer-Template/figs/P4.png)



## Tips

如果使用[Latex Workshop](https://github.com/James-Yu/LaTeX-Workshop)，可以在配置文件中添加删除文件配置，以免造成编译后过多文件

~~~json
  "latex-workshop.latex.clean.enabled": true,
  "latex-workshop.latex.clean.fileTypes": [
    "__latexindent_temp.*",
    "*.smn",
    "*.vrb",
    "*.nav"
  ],
~~~

