# Vue（v-xxx）
## 一些小例子
## 注意：
- v-click：=可以缩写为@click
- 有时候使用方法，有时是属性。如果把methods，computed互换则报错。
- Vue-inserted例子中：
点击div内部log“in”，点击外面log“out”，浮层也是这样的道理。
- 钩子函数参数：
指令钩子函数会被传入以下参数：
binding：一个对象，包含以下属性：
1.value：钩子的参数，eg：&lt;div 2.v-click-outside="close"></div>,这个close就是value。
3.name:指令名，不包括v-前缀。（还有其他，此处没写）以上出自Vue文档。
vNode：虚拟节点。
