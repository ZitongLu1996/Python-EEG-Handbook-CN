# **Python脑电数据处理中文手册 v0.1**  

编者：  
- 路子童 - 俄亥俄州立大学  
- 李婉如 - 北京大学  
- 聂露 - 中山大学
- 赵匡是 - 心仪脑

如对本教程有任务疑问或建议，欢迎通过以下方式联系：  
1 在公众号”路同学“后台留言  
2 邮件联系路子童，邮箱为zitonglu1996@gmail.com

***

**几乎所有脑电初学者都是从 EEGLAB 开始接触脑电预处理过程的，EEGLAB 浅 显直观的 GUI 界面再或是基于 MATLAB 的代码操作影响了一代脑电人。然而，随 着简洁、易上手的 Python 语言的快速发展，其丰富的社区资源也扩张到了认知 神经科学领域。MNE-Python、Nilearn、Nibabel 等等相关工具包层出不穷，让我 们有机会开始使用 Python 来对进行各种神经数据进行分析处理。遗憾的是，它 们未能在国内迅速地普及，相对门庭冷淡。**  

**为了弥补这一空白，一方面希望更多人加入到使用 Python 的行列中来，另 一方面希望为更高阶的脑电数据操作架起桥梁，我们尝试完成一个中文版的 Python 脑电处理教程，它便是这个《Python 脑电数据处理中文手册》。**  

**自己编程不好怎么办?“感觉用 Python 做数据处理好难学不会怎么办?”。 诚然，完全基于代码的数据处理往往会带给很多人一些担心。但是，我们希望能 在这里通过我们的手册告诉你们，不需要惧怕，只要一步一步跟着学习与理解， 你的编程能力一定会有所提升、你一定可以学会!**  

**十分开心与激动，有愿意一起参与到这个手册编撰的小伙伴，很感激自己硕 士三年与一群极其优秀的人在同一个 Lab 共事，也很荣幸大家与我一样愿意加入 到这个自愿分享、支持开源的行动中来。一开始我们就本着严谨、真诚、公益的 态度来规划这件事情，并花费了许多精力将它尽可能地做到最好，尽可能将这个 手册已最好、最全面的方式呈现到各位面前。**  

**目前，这个中文手册主要分成了两个部分，单被试预处理篇和多被试分析篇。 在单被试预处理篇中，我们参考了贾会宾老师的《EEGLAB 中文手册》以及 Steven Luck 的《事件相关电位基础》，我们旨在写一个基于 Python(主要是基于 MNE- Python 工具包)的对单个被试脑电数据进行预处理的标准化流程。虽然我们努 力想呈现出一个“傻瓜式”的教程，但是我们依然不建议完全没有任何编程基础 和脑电基础知识的人员盲目使用。**  

**在多被试分析篇中，我们首先从常见的 Python 数据操作、数据的读取与存 储以及基础统计分析与实现等方面着手，让大家具备一定的基本数据分析能力后 再进入到更高阶的数据处理中。我们也必须承认，高阶的分析在理解难度和实现 难度上一定是要高于预处理部分的。但是，只要你仔细阅读每一句手册里的说明、 结合注释理解每一行代码、自己亲手一步一步实现一遍，你肯定能收获很多。**  

**衷心希望我们的手册能提供一些思路与建议，它当然无法完完全全直接适用 于你自己的数据，但我们相信，只需要一些并不困难的修改之后，兴许你就能自 如地开始着手处理自己的数据了。所谓“授人以鱼不如授人以渔”，望读者们能 举一反三。手册里也许很多地方的内容未必深入，因此，这其中的内涵与奥秘、 技巧与思想，都需要读者在不断的体验中去用心体会、在实战中不断积累经验。**  

**完成这个中文手册花费了我们巨大的心血，在一定程度上来说他不仅仅是一 个脑电的数据处理手册，更是对广大初入心理学与神经科学领域的研究人员的一 个 Python 入门手册。当然，我们也希望这个中文手册是国内 Python 脑电数据处 理中文手册的第一步，但也不仅仅是第一步!**  

**十分感激读者在使用过程中给我们反馈建议与意见，也欢迎大家多多分享我 们的手册让它能帮到更多人，愿此手册与我们、与读者共同进步!**

***

**你们的转发、分享与建议是我们继续进一步制作更深入文档的动力**  
**以及，欢迎关注公众号：路同学**
