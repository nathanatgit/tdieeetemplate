这个不是天大毕业论文模板，应付普通大作业/结课报告用的
-----------------------

TDReportTemplate.tex

整体风格基于IEEE英文论文模板

所以推荐交英文大作业/报告时使用

-----------

要用中文标题，比如参考文献，图1，表1等，请使用TDReportTemplate_CN_TITLE.tex，也是基于IEEE

~~看着很奇怪就是了~~

其实我只想用IEEE模板写个英文报告，加个天大封皮

~~所以只用封皮就可以了~~

github已有很多天大中文的毕业论文模板，所以要想用比较符合中文格式的报告模板可以直接用那些

---------------
字号，行间距，缩进等修改请参考IEEEtran_HOWTO.pdf
模板没有对IEEEtran.cls修改（patchcmd很好用）

IEEE模板有很多样式，journal， conference等，可以更改第一行\documentclass参数来修改，参考IEEEtran_HOWTO.pdf（比如conference的页码就在底部）

-----------
编辑环境为Windows+VSCode+Latex-Workshop extension+texlive2018，（已知mac和linux中文显示会跟Windows不同，控制序列\songti不可用）不保证其他平台可用性....请参考ctex手册对照自己平台修改...
