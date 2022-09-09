- 常见的正则表达式
- 事件冒泡：依次向内捕获，然后向外冒泡。[例题](https://www.nowcoder.com/questionTerminal/c018564977104c53a094025e9fb92d83)
- cookie与localStorage [练习](https://www.nowcoder.com/questionTerminal/96977c22b17a456d9131a6abd7722cf1)
- 作用域与 setTimeout

- js 模块

js 中现在比较成熟的有四种模块加载方案。
第一种是 CommonJS 方案
第二种是 AMD 方案
第三种是 CMD 方案
第四种方案是 ES6 提出的方案，使用 import 和 export 的形式来导入导出模块。

补充一下他们的区别：
AMD和CMD都是浏览器端的JS模块化规范，分别由require.js和sea.js实现
CommonJS是服务器端的js模块化规范，由NodeJS实现

- Redux遵循的原则：
（1）单一数据源：整个应用的state被存储在一棵object tree中，并且这个object tree只存在于唯一一个store中；
（2）state是只读的：唯一改变state的方法就是触发action，action是一个用于描述发生事件的普通对象；
（3）使用纯函数修改数据；
