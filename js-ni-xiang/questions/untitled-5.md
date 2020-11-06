---
description: 浏览器工具F12后进入无限的debugger模式
---

# 1. 无限debugger

如下代码：    

JS学习网站 ：[https://www.runoob.com/js/js-function-definition.html](https://www.runoob.com/js/js-function-definition.html)

自执行函数方式 ： [https://segmentfault.com/a/1190000006813113](https://segmentfault.com/a/1190000006813113)



```text
JS 函数的call 属性 
(function() {
    return !![]  
} ["constructor"]("debu" + "gger")["call"]("actio]
```

1. 自执行函数 
2. JS的constructor 构造函数 
3.  函数对象的属性 call 调用函数执行

```text
JS 函数的apply 属性
func.apply(thisArg, [argsArray])
```

`thisArg`必选的。在 _`func`_ 函数运行时使用的 `this` 值。请注意，`this`可能不是该方法看到的实际值：如果这个函数处于[非严格模式](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Strict_mode)下，则指定为 `null` 或 `undefined` 时会自动替换为指向全局对象，原始值会被包装。

`argsArray`可选的。一个数组或者类数组对象，其中的数组元素将作为单独的参数传给 `func` 函数。如果该参数的值为 [`null`](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/null) 或  [`undefined`](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/undefined)，则表示不需要传入任何参数。从ECMAScript 5 开始可以使用类数组对象。 [浏览器兼容性](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Function/apply#Browser_compatibility) 请参阅本文底部内容。

![&#x622A;&#x56FE; apply &#x65E0;&#x7EBF;debugger](../../.gitbook/assets/image%20%284%29.png)



