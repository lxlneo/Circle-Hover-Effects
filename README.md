Circle-Hover-Effects
====================

css 圆形hover 效果 
--
> 学习使用css 过渡属性 transition
语法：
--
transition：[ transition-property ] || [ transition-duration ] || [ transition-timing-function ] || [ transition-delay ]

默认值：看每个独立属性
--
适用于：所有元素，包含伪对象:after和:before
继承性：无

取值：
-----

> [ transition-property ]： 检索或设置对象中的参与过渡的属性 

> [ transition-duration ]： 检索或设置对象过渡的持续时间 

> [ transition-timing-function ]： 检索或设置对象中过渡的动画类型 

> [ transition-delay ]： 检索或设置对象延迟过渡的时间 

示例
----
-------------------------
> transition:border-color .5s ease-in .1s

> 意思是 border-color 属性 延迟0.1s 执行变化耗时0.5s 使用动画类型为ease-in 线性模式.

-------------------------
多个属性连写
----
> transition:border-color .5s ease-in .1s, background-color .5s ease-in .1s, color .5s ease-in .1s;

***当然不要忘了写前缀
---