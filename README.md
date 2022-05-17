# 基于崔效瑞老师的mini-vue而来，用于深入学习 vue3 源码

为什么叫 `mini-vue3-plus`，因为它是基于崔效瑞老师的开源库mini-vue而来，在mini-vue的基础上实现更多的vue3核心功能，用于深入学习 vue3， 让你更轻松地理解 vue3 的核心逻辑。

目前已经实现：

- [x] 模板引用ref：[Vue3 模板引用 ref 的实现原理](https://juejin.cn/post/7087227183613083678)
- [x] 生命周期：[Vue3生命周期Hooks的原理及其与调度器(Scheduler)的关系](https://juejin.cn/post/7093880734246502414)
- [x] 调度器Scheduler：[Vue3生命周期Hooks的原理及其与调度器(Scheduler)的关系](https://juejin.cn/post/7093880734246502414)
- [x] watch watchEffect [Vue3 的 effect、 watch、watchEffect 的实现原理](https://juejin.cn/post/7098303741278814221)



崔效瑞老师还把他的mini-vue库的实现做成了视频教程，大家如果想学的话，也可以扫码进行学习。

读懂 Vue3 源码可能是 2022 年要进大厂的必经之路了。

但是直接阅读源码的难度非常大，因为除了核心逻辑以外框架本身还要处理很多 edge case(边缘情况) 、错误处理、热更新等一系列工程问题。

因此我向大家推荐大崔哥的 mini-vue 来简化学习 vue3 源码的难度 ，这个库把 vue3 源码中最核心的逻辑剥离出来，只留下核心逻辑，以供大家学习，带有详细的中文注释，以及完善的输出，帮助你理解运行时流程。

mini-vue 这个库在 github 上已经获的 6.2k 的 star，完成了 reactivity、 runtime-core、 compiler 三个大模块的简化。

现在大崔哥基于 mini-vue 推出了视频课程，他会带你手把手的实现同级别的 mini-vue 库，授课方式非常有特点，他会先带你写一个单元测试（目标），然后写代码让单测通过（实现），最后在使用重构手法让代码变的更可读。 代码组织方式和代码的命名也完全遵照 vue3 源码。课程里面没有跳过一行代码。同时还融入了 TDD 、 小步骤的开发思想、 TPP 从具体到抽象等编程思想层面的内容。

想掌握源码的话，最好的方式就是手写一遍，而这套课程的教学理念就是展现出编程问题背后的思考全过程，对于想掌握 vue3 原理、冲击大厂、进阶中高级前端的同学非常适合，是目前市场上少见的好课。

 ![](https://user-images.githubusercontent.com/24350739/159156982-ad40a43a-e312-4e06-a843-cf77f27d1f3e.jpg)



