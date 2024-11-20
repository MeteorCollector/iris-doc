# iris tex

基于iris本地环境的LaTeX公式图片生成功能（目前默认白色背景，因为透明背景在手机qq上打开根本看不见），在群聊和私聊中都可以使用。

指令打成`tex`,  `Tex`, `latex`, `Latex`, `LaTeX`均可以识别。

示例：

`iris tex i\hbar\frac{\partial \psi}{\partial {t}} = \frac{-\hbar^2}{2m} \left( \frac{\partial^2}{\partial {x^2}} + \frac{\partial^2}{\partial {y^2}} + \frac{\partial^2}{\partial {z^2}} \right) \psi + V \psi `

`iris tex \begin{aligned}dQ=dU+pdV&\Rightarrow(C_m-C_{V,m})dT=pdV;\\pdV+Vdp=RdT&\Rightarrow(\dfrac {C_m-C_{V,m}}{R})(pdV+Vdp)=pdV;\\C_{p,m}=C_{V,m}+R&\Rightarrow(C_m-C_{p,m})\dfrac {dV}V+(C_m-C_{V,m})\dfrac {dp}p=0;\\pV^n=Const&\Rightarrow n=\dfrac{C_m-C_{p,m}}{C_m-C_{V,m}};\\C_{p,m}=\dfrac{\gamma}{\gamma-1}R,C_{V,m}=\dfrac{1}{\gamma-1}R&\Rightarrow C_m=\dfrac{n-\gamma}{(n-1)(\gamma-1)}R\\&\Rightarrow C_m=C_{V,m}\dfrac{\gamma-n}{1-n}.\end{aligned}` (credit: mike3090)

现在已经支持发送的信息中换行。另外，关于LaTeX公式生成，推荐[这个网站](https://www.latexlive.com)。
