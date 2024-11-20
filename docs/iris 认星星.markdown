## 星空识别

iris的星空识别基于网站[https://nova.astrometry.net/](https://nova.astrometry.net/)

可以识别出来的星空基本都是正确的，但是如果照片后期处理幅度很大（例如一些星野照片中会调整一些星星的亮度，尤其是在处理银河时）、或者拍摄条件不是很好（例如星点太少或者有太多云和遮挡物）、拍摄条件特殊（例如很奇怪的波段或者填色），很有可能无法识别。

`iris 认星星/认星 <图片>`用来提交图片进行识别，请勿滥用。

如果提交成功，会返回一个subid。你可以用 `iris 认星星/认星 查询 <subid>` 来查询工作状态（工作完成后iris会自动将结果发到群里）；

或者你可以用 `iris 认星星/认星 -ls` 来查询本群中所有工作的subid

示例：

<p><img src="StarRecog1.jpg" width="60%" align="middle" /></p>
<p><img src="StarRecog2.jpg" width="60%" align="middle" /></p>

