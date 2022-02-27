# Latex-

# 中文环境

设置->修改Latex引擎->选择“XeLatex”。
```
\usepackage[UTF8, scheme=plain, punct=plain, zihao=false]{ctex} (可以避免,日期什么的变成中文格式)
\usepackage[T1]{fontenc}

在begin{document}下,进行全局字体, 字号的描述
\kaishu \zihao{-5}

    {\songti 宋体}
    
    {\heiti 黑体}
    
    {\fangsong 仿宋}
    
    {\kaishu 楷书}
```
参考文档: https://www.jianshu.com/p/03c121c0868d
