#### 3.7.1 理解参数

ECMAScript中，函数的参数传递：

- 无所谓传递几个
- 无所谓参数类型

与你的定义无关。因为ECMAScript的参数在内部是以一个**数组**表示的。且在函数体内部可以通过arguments对象来访问该参数数组，从而获取传递给函数的每一个参数。

e.g. 第一个元素 `arguments[0]`，第二个元素`arguments[1]`

**命名的参数只提供便利，但不是必须的。**

- 可通过`arguments`对象的`length`属性获知传了多少参数并进行对应操作


[示例代码](https://jsrun.net/84gKp/edit)

#### 3.7.4 没有重载

ECMAScript中定义两个相同名字的函数，则后一个生效。

[示例代码](https://jsrun.net/94gKp/edit)

### 3.8 小结

