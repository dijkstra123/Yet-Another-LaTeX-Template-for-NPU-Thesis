**描述您的问题 (Describe the bug)**

在windows系统下使用ctex2.9编译失败

**环境与版本信息**

1. 代码版本(Code version)（留空则默认最新）：
2. 操作系统 (OS)：windows 11
3. Tex Live版本，其他Tex版本也请注明 (Version of Tex Live or other Tex distribution)：*CTeX*_2.9.2.164_Full
4. Tex 编译器 (Tex compiler, eg. XeTeX): Xelatex

**错误内容 (Error contents)**

! Undefined control sequence.
l.263 \theorempreskip
                     {0pt} 

**可复现内容 (Reproduceable steps)**

xetex等均无法编译，会报错：

! Undefined control sequence.
l.19 \documentclass
                   [lang=chs, degree=phd, blindreview=false, adobe=true]{yan...
