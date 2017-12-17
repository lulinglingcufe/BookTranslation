# LaTeX翻译模板使用说明
* 在浙大博士论文模板```zjucs_thesis```的基础上，结合```BookForTranslation```文件，初步设置了翻译排版格式。 
* 本人使用的是是ctex套装，winEdt编辑器。这是ctex套装的下载地址 http://www.ctex.org/CTeXDownload

1.```zjucs_thesis\main.tex```可以使用xelatex引擎编译。如果不想看其他章节的内容，只要在```zjucs_thesis\main.tex```中把那部分注释掉即可。
模板中也注释了原有的“参考文献”等部分，如下所示。
```
......
%  \chaptermarknn{参考文献}
%\bibliographystyle{ZJUthesis}
%\bibliographystyle{aaa}
%==============================================================
%  \include{data/publications}
%  \include{data/thanks} 
.....
```

2.模板中加入了```BookForTranslation\FigsCodeLatex\header.tex```的部分代码，因此可以显示如下所示的代码段。
