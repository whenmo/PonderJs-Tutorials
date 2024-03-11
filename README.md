# PonderJs Tutorials

## 起源

> 截止至本篇教程开始编写的时间(2024.03.07),我没有在市面上发现任何一篇对新手较为友好的教程(GitHub 上的 wiki 和没有一样)
> 因此,在本篇教程,我会将我所掌握的所有 PonderJS 知识全盘托出.但是我会的也不算多,基本都是相对基础的知识,但是写一个简单的 Ponder 基本也都是够了.

## 声明

> 本人会的知识与真正的大佬比起来并不算多,相对基础.因此本篇教程所教的东西都是在 Ponder 里很基础很简单的,至于复杂一点的(例如纹理连接,IE 的各种工作站等)我会在学会后尽早补上

本篇教程基于 KubeJs 6 编写,在此之前我也写过 KubeJs 5 的,各种方法没有区别,唯一的区别就是开头的事件声明(截止我已发现的)

### KubeJs 5

```js
onEvent("ponder.registry", (e) => {});
```

### KubeJs 6

```js
Ponder.registry((e) => {});
```

## 所需要的工具

- 七根木棍(梯子)
- PonderJS (低于 1.18.2),Ponder for KubeJS (高于等于 1.18.2)以及它们的前置
- ProbeJs
- 那么 **一丢丢** 🌌🤏的 KubeJs 基础