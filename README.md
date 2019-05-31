# Vue（v-xxx）
## 一些小例子
## 注意：
- v-click:=可以缩写为@click
- 有时是使用方法，有时是属性。如果把methods，computed互换则报错。
- Vue-inserted例子中：
点击div内部log“in”，点击外面log“out”，浮层也是这样的道理。
- 钩子函数参数：
指令钩子函数会被传入以下参数：
binding：一个对象，包含以下属性：
&ensp;1.value：钩子的参数，eg：&lt;div-click-outside="close"></div>,这个close就是value。
&ensp;2.name:指令名，不包括v-前缀。（还有其他，此处没写）以上出自Vue文档。
vNode：虚拟节点。
- Vue过渡：
 过渡的类名：（用完就扔系列，这些使用完不会存在html中）
 &ensp;v-enter：开始状态
 &ensp;v-enter-active: 定义进入过渡生效时的状态
 &ensp;v-enter-to: 2.1.8版及以上 定义进入过渡的结束状态
 &ensp;v-leave: 定义离开过渡的开始状态
 &ensp;v-leave-active：定义离开过渡生效时的状态。
 &ensp;v-leave-to: 2.1.8版及以上 定义离开过渡的结束状态。
 **不明白的参考例子**
 - Vue过渡-velocity：
 如果部分不成，可能是velocity版本问题，换成1.2.3试试 。
- Vue动画多元素
&ensp;别忘记加key="xxx"：
&ensp;&ensp;开始Vue只会认为你要变的是button里面的内容，加上可以，才知道把两个button切换。
- mode="out-in":
爱我button先消失，爱他button再显现。使动画依次执行而不是同时。见Vue动画集合之toggle。

