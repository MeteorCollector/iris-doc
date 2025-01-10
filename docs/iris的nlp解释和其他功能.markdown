## iris的问句应答

群聊中，在功能”应答“开启时（默认开启），iris可以对一般疑问句进行随机应答。

群聊中，在功能”全应答“开启时（默认开启），iris将基于语料库对所有未识别的语句进行应答。

在2025年1月10日之前，该nlp没有任何机器学习成分，完全基于字符串的相似度从语料库中找到最”相似“的问句，然后返回对应的回答。再注意，iris的语料库是天文特化的，并不能用于闲聊。欢迎同好补充天文知识。语料库的详细信息详见[这个仓库](https://github.com/MeteorCollector/iris_AstroQnA_ZH)。

在2025年1月10日之后，iris接入了deepseek，但是仍使用之前的语料库做 prompt engineering，也就是说投喂语料库还是有用的。

如若对iris的早期nlp感兴趣，强烈建议阅读该文章：[iris的nlp之路：章鱼触手与斩龙大剑](https://meteorcollector.github.io/2023/05/iris-fake-nlp/)

## 存图片（为了应对QQ表情包无法保存实现的功能）

大喊“iris 我要存图”，iris会将最近一个图片的网页链接发送出来，进入保存即可。

私聊群聊都可以。

<p><img src="SendImg1.jpg" width="60%" align="middle" /></p>
<p><img src="SendImg2.jpg" width="60%" align="middle" /></p>

