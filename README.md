# nuaathesis2024
南京航空航天大学研究生毕业论文Latex模板（非官方）

模板**完全**参考https://github.com/nuaatug/nuaathesis.git 修改

只保留了研究生中文模板，旨在精简易用

## 修改内容

### 1、解决“Undefined control sequence”报错

将\usepackage{enumerate}替换\usepackage{enumitem}

### 2、注释掉cls中的tex和math宏

### 3、将标题中的英文显示为新罗马字体

cls中1114行和267行的\sffamily删除（demo文件夹外边的cls管用）

## 运行环境

overleaf 2024  https://www.overleaf.com

直接创建新项目上传zip文件，编译器修改为Xlatex，编译即可
