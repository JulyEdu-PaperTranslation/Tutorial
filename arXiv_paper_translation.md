## 如何在 arXiv 源代码上翻译##
### 下载源代码 ###
* 在 [arxiv](https://arxiv.org/)中搜索文章
* 在 "down load" 下. 点击"Other format"
* 点击 "download source"
 
### latex 配置 ###
* latex in linus: 
 - Short:[latex  安装与中文配置](http://blog.sina.com.cn/s/blog_7101508c0100tcb4.html)
 - Long:[LaTex Ubuntu中文环境安装与使用](http://www.mikewootc.com/wiki/tool/doc_process/latex_chinese_ubuntu_setup.html)
* latex in windows:
 - [LaTeX新人教程, 30分钟从完全陌生到基本入门(转)](http://www.mikewootc.com/wiki/tool/doc_process/latex_tutor.html)
* 在源代码添加如下的两行 
 > **\usepackage{xeCJK}  %必须加xeCJK包**
 >
 > **\setCJKmainfont{AR PL UMing CN}  %换成本地字体**
 >
 > [例子](https://github.com/JulyEdu-PaperTranslation/DeepLearning/blob/master/conditional_generative_adversarial_networks/workshop.tex)
 
* 背景加入水印
 - [如何给你的文章添加背景与水印](http://blog.sina.com.cn/s/blog_5e16f1770102fd25.html)
