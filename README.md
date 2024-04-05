# **Python脑电数据处理中文手册 v2.0**  

编者：  
- 路子童 - 俄亥俄州立大学  
- 李婉如 - 北京大学  
- 聂露 - 中山大学
- 赵匡是 - 博睿康

如对本教程有任务疑问或建议，欢迎通过以下方式联系：  
1 在公众号”路同学“后台留言  
2 邮件联系路子童，邮箱为zitonglu1996@gmail.com

***

第一章: 单被试预处理:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ZitongLu1996/Python-EEG-Handbook-CN/blob/master/EEG_CN_Python_Handbook_Preprocessing.ipynb)

第二章: 基础Python数据处理:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ZitongLu1996/Python-EEG-Handbook-CN/blob/master/EEG_CN_Python_Handbook_DataOperations.ipynb)

第三章: 多被试分析:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ZitongLu1996/Python-EEG-Handbook-CN/blob/master/EEG_CN_Python_Handbook_MultisubjectsAnalysis.ipynb)

第四章: 高级脑电数据分析:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ZitongLu1996/Python-EEG-Handbook-CN/blob/master/EEG_CN_Python_Handbook_AdvancedAnalysis.ipynb)

***

### 依赖环境与依赖包

Python >= 3.6
MNE >= 1.6
NeuroRA >= 1.1.6.11
inverted-encoding == 0.2.3

***

**三年前，我们在硕士毕业/进入工作/博士生涯开始前的暑假怀着满腔热情与忐忑发布了《Python脑电数据处理中文手册》第一版。自那以来，我们收到了广大读者的强烈反响与宝贵意见。我们的GitHub项目已经收获了232颗Stars，我的邮箱也时不时会有咨询相关问题的邮件（有部分邮件可能因为邮件太多忘记回复、也可能由于有些问题实在过于基础可以通过其他途径找到答案而没有回复）。**  

**当然，第一版并不是完美的，之后会进行更新也是我们在三年前发布第一版时就有所计划的。我们希望可以不断地完善这个手册、修改旧版本里可能存在的问题、去优化与丰富我们的内容。同时，相关的依赖Python包也在不断更新，随之而来在手册里我们也必然需要进行一些修改。因此，这些因素都是我们更新第二版的基础。同时，非常高兴看到大家开始参考与使用这个手册，这也是对我们整个作者团队莫大的肯定。也正是大家这些正向的反馈激励我们继续前行，而带给了我们更新第二版的动力。**  

**在第二版中，我们对手册的结构进行了重新的划分，分成了四个大的章节：单被试预处理、基础Python数据处理、多被试分析、以及高级脑电数据分析。我们主要修改了前一版中出现的一些笔误或描述性错误，在多被试分析章节中介绍了事件相关电位分析与时频分析，而将基于分类的脑电解码和表征相似性分析的部分归类到了高级脑电数据分析章节中，并额外增加了反向编码模型的部分。**  

**于此同时，在三月初也发布了英文版的Python EEG Handbook （英文版预印本见PsyArXiv：[https://osf.io/preprints/psyarxiv/dcmke](https://osf.io/preprints/psyarxiv/dcmke)），希望这一手册不仅仅在中文社区、也在英文社区帮助脑电研究人员或希望踏入脑电领域的初学者。**  

**我们希望《Python脑电数据处理手册》（无论中文或英文版）能一直作为一个桥梁，不仅仅连接过去和未来，也连接初学者与专家、研究者与开发者，来共同推进脑电数据分析的发展。更重要的是，我们希望通过这一本手册不仅仅能帮助你在技术上取得进步，更能激发你对认知神经科学更深的热爱与探索！**  

**再次感谢所有人的支持，期待与你们在学术的路上相遇！**  

***

**你们的转发、分享与建议是我们继续进一步制作更深入文档的动力**  
**以及，欢迎关注公众号：路同学**
