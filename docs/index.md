# 写在前面

<p><img src="iris_star.jpg" width="100%" align="middle" /></p>

iris 是一个天文科普机器人，完全由监护人独立编写，诞生于2022年8月24日。曾经“不想在社团宣传群里一边又一遍地发招新信息”的代劳工具如今变成了广受喜爱的大项目，也是我一开始没有想到的。iris最开始运行在 Mirai 框架上，接着移植到了 go-cqhttp，现在使用 nonebot 框架接入 nt 架构的 QQ。iris 的内核使用 C# 编写，一些外接功能采用 python 实现。由于在其他地方的介绍已经详尽，本页面更多地用于新闻发布和页面传送。

如果想要了解iris的全部功能，请继续阅读本文档。

如果想要了解iris的自然语言处理部分，请阅读：[iris的NLP简记](https://meteorcollector.github.io/2023/05/iris-fake-nlp/)

## 原版manual

这一版的manual是从 [gitpage](https://meteorcollector.github.io/2022/10/iris-manual/) 迁移过来的，也可以到原网站看看，不过内容是一样的。

## 同人作品

可以到 [铱站](http://the-shell-of-iris.site/index.html) 看看更多 iris 相关内容。

## 铱之皮套

或许你可以到 [这里](https://meteorcollector.github.io/2023/02/iris-l2d/) 看看铱之皮套。

## 免责声明
iris的群友们通过iris获得的所有内容均为**自动生成**，与iris的观点**完全无关**。请在知晓这一点的前提下与iris进行互动。

## 规则怪谈
iris天文竞赛的**时钟**运行得不甚稳定。如果时钟停止运行，请第一时间联系她的监护人。

## 征集公告
iris长期征集天文题库。详见 [这篇文章](https://meteorcollector.github.io/2022/08/the-birth-of-iris/) 的“天文竞赛”一节。

## 重要提醒

在这里对一些使用者经常犯的错误进行**特殊提醒（每一条都很重要）**：

1. 指令字段之间要**加空格**。指令字段之间要**加空格**。指令字段之间要**加空格**。例如：`iris 发 星图 秦皇岛` 之间的空格并不是为了排版显示好看，而是**真的要打空格**。如果说得更明显一些，你应该输入`iris<空格>发<空格>星图<空格>秦皇岛`（不包括引号和尖括号）；
2. 下面示例中的尖括号“<>”仅仅是在提示你这里应该输入一个变量，**而不是**提醒你输入的时候要加尖括号；好比说你要查询恒星“长沙”的信息，`iris 发 恒星 <arg>` 指令的使用方法**并不是**让你输入 `iris 发 恒星 <长沙> `，而是应当输入： `iris 发 恒星 长沙 `。**请把括号去掉**；
3. 如果实在拿不准要输入什么，可以**直接复制示例指令**进行尝试，不要自己穷举语法；
4. 对iris友善一些，毕竟她对你真的很有耐心。

## ! 更重要的提醒 !

请**确保**你已经记住了**“重要提醒”**中的内容再继续阅读。

## 新闻

### iris 两周年了！(2024.8.24)

iris 是哪里的......南大、武大、哈工大，傻傻分不清？iris 占领全国了没有？

推送： [iris 两周年！ (meteorcollector.github.io)](https://meteorcollector.github.io/2024/08/iris-2nd-anniversary/)



### iris获得南京大学民间年度人物提名 (2023.12.31)

在2023年度“小破手”杯南京大学年度评选中，iris获得**“年度人物”**提名并在30个候选提名中得票第15位。

“小破手”杯南京大学年度评选是“南哪助手”主办的每年一度的年度评选活动，设有“年度汉字”、“年度人物”、“年度事件”等评选项目。本次投票中，共收到430人次有效提名，获得3688条投票（有效样本数3664）。

原文链接：[第三届南哪年度评选结果公布！](https://mp.weixin.qq.com/s/wVHx1HhBruFWlaR2rE1ddg)



### 第一个中文天文大语言模型StarGLM发布，iris语料库获引用 (2023.9.20)

(现StarGLM仓库已迭代至StarWhisper)

> 我们整合了天文科学教育联盟、司天工程、集思谱文献平台相关的语料数据与知识库资料，训练得到了天文大模型StarGLM(ChatGLM for Star)，以期缓解大语言模型在天文专业的幻觉现象，为接下来可处理天文多模态任务、部署于望远镜阵列的观测Agent——司天大脑（数据智能处理）打下基础。（引自StarGLM仓库介绍）

StarGLM的V1版本在CG-Eval[23/10/15]评测上的结果，总排名达到第二，仅次于GPT-4，数学推理和天文能力接近或超过GPT 3.5 Turbo。

iris使用的天文问答对语料库在专家订正部分起到作用。

链接：[StarWhisper](https://github.com/Yu-Yang-Li/StarWhisper/)   [iris_AstroQnA_ZH](https://github.com/MeteorCollector/iris_AstroQnA_ZH)