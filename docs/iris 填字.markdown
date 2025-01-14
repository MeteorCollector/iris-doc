# iris 填字

匹配规则：

>N -> 随机一位数字
>
>M -> 随机数字，范围[1, 12]
>
>D -> 随机数字，范围[1, 31]
>
>H -> 随机大写十六进制数码，范围[0, F] (Hu与其效果相同)
>
>Hl -> 随机小写十六进制数码，范围[0, f]
>
>A -> 随机一级汉字
>
>B -> 随机二级汉字
>
>Q -> 随机中国地级行政单位名称
>
>R -> 随机中国县级行政单位名称
>
>X -> 随机中国姓氏
>
>[l_bound:h_bound] -> 随机数，范围[l_bound, h_bound]
>
>限定符：在A, B, Q, R, X后添加小写字母，则脚标相同的相应字母替换内容在同一条内保持一致
>
>转义符：反斜杠后的大写字母不会被替换。例如\A，\Q等

示例1：
```
	iris 填字 Qa大学将在周[1:7]解封并执行NN小时核酸查验制度，请全体同学注意QaAA码信息，及时上报。另外，请于M月D日之前到达过Q、Q、Q的同学主动联系辅导员。
```
返回1：
```
	兰州大学将在周2解封并执行74小时核酸查验制度，请全体同学注意兰州戎衍码信息，及时上报。另外，请于5月18日之前到达过邢台、晋中、庆阳的同学主动联系辅导员。
```
示例2：
```
	iris 填字 Ai情就是命令，防Ai就是责任
```
返回2：
```
	你情就是命令，防你就是责任
```
示例3：
```
	iris 填字 SS\R RA人XAA QAA寺
```
返回3：
```
	SSR 浦口能人艾携猴 商洛唐廷寺
```

*特别鸣谢：iris的好姐姐🐟姐贵在姓氏库、县级行政单位库所做的贡献。*