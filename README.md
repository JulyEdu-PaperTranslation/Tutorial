# 成员使用指南 #

## 文章翻译 repository 结构 ##
* 每个文章分类对应一个repository, 由翻译组或者管理员创建
* 每篇文章对应一个sub-directory，由翻译组创建（比如：DeepLearning/Conditional_Generative_Adversarial_Networks）
* README.md 请指出文章标题，翻译人员名单，以及翻译文本下载地址(比如：https://github.com/JulyEdu-PaperTranslation/DeepLearning)
* 每一篇文章翻译请选出组长，并规定只有组长以及管理员可以修改master branch,其他成员则需要通过pull request.
* 如果能找到文章中实现算法的源代码，请将源代码加入到repository中，以便于读者查找和调试使用

## 如何在 arXiv 源代码上翻译##
### 下载源代码 ###
* 在 https://arxiv.org/ 中搜索文章
* 在 "down load" 下. 点击"Other format"
* 点击 "download source"
 
### latex 配置 ###
* 在源代码添加如下的两行 

** \usepackage{xeCJK}  %必须加xeCJK包 **

** \setCJKmainfont{AR PL UMing CN}  %换成本地字体 **

* 例子: https://github.com/JulyEdu-PaperTranslation/DeepLearning/blob/master/conditional_generative_adversarial_networks/workshop.tex
