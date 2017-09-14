# JavaScript 常见问题

## 一般问题

### JavaScript 和 Java 有什么联系

二者其实毫无关系。

JavaScript 和 Java 有一些共性但是在另一些方面有着根本性区别。JavaScript语言类似 Java 但是并没有 Java 的静态类型和强类型检查特性。JavaScript 遵循了 Java 的表达式语法，命名规范以及基础流程控制，这也是 JavaScript 从 LiveScript 更名的原因。

与 Java 通过声明式构建类的编译时系统不同，JavaScript 采用基于少量的数据类型如数字、布尔、字符串值的运行时系统。JavaScript 拥有基于原型的对象模型提供的动态继承；也就是说，独立对象的继承是可以改变的。 JavaScript 支持匿名函数。 函数也可以作为对象的属性执行。

与 Java 相比，Javascript 是一门形式自由的语言。你不必声明所有的变量，类和方法。你不必关心方法是否是 共有、私有或者受保护的，也不需要实现接口。无需显式指定变量、参数、方法返回值的数据类型。

Java 是基于类的编程语言，设计的初衷就是为了确保快速执行和类型安全。类型安全，举例来说，你不能将一个 Java 整数变量转化为一个对象引用，或者由Java字节码访问专有存储器。Java基于类的模型，意味着程序包含专有的类及其方法。Java的类继承和强类型要求紧耦合的对象层级结构。这些要求使得Java编程比JavaScript要复杂的多。

相比之下，JavaScript 传承了 HyperTalk 和 dBASE 语句精简、动态类型等精髓，为更多开发者提供了一种语法简单、内置功能强大以及用最小需求创建对象的编程工具。

| JavaScript                               | Java                                     |
| ---------------------------------------- | ---------------------------------------- |
| 面向对象。不区分对象类型。通过原型机制继承，任何对象的属性和方法均可以被动态添加。 | 基于类系统。分为类和实例，通过类层级的定义实现继承。不能动态增加对象或类的属性或方法。 |
| 变量类型不需要提前声明(动态类型)。                       | 变量类型必须提前声明(静态类型)。                        |
| 不能直接自动写入硬盘。                              | 可以直接自动写入硬盘。                              |

### JavaScript 和 ECMAScript 有什么联系

JavaScript 的标准化组织是 [ECMA](http://www.ecma-international.org/) ——这个欧洲信息与通信系统标准化协会提供基于 Javascript 的标准化方案（ECMA 原先是欧洲计算机制造商协会的首字母缩写）。这种标准化版本的 JavaScript 被称作 ECMAScript，在所有支持该标准的应用中以相同的方式工作。公司可以使用开放标准语言来开发他们自己的 JavaScript 实现版本。ECMAScript 标准在ECMA－262规范中进行文档化。 参照 [JavaScript的新特性](https://developer.mozilla.org/en-US/docs/Web/JavaScript/New_in_JavaScript) 以便学习更多关于不同版本的 JavaScript 和 ECMAScript 规范版本。

ECMA-262 标准也通过了 国际标准化组织（[ISO](http://www.iso.ch/)）的 ISO-16262。你可以[在这里](http://www.ecma-international.org/publications/standards/Ecma-262.htm)找到该规范文件。 ECMAScript 规范并没有描述文档对象模型（[DOM](https://developer.mozilla.org/zh-CN/docs/Web/API/Document_Object_Model)），该模型由 万维网联盟（[W3C](http://www.w3.org/)） 制定。DOM 定义了HTML文件对象被脚本操作的方法。为了更清楚地了解当使用JavaScript编程时用到的不同技术，请参阅 [JavaScript 技术概述](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/JavaScript_technologies_overview)。

**JavaScript 文献 和 ECMAScript 规范**

ECMAScript 规范是一套用于实现 ECMAScript 的要求。如果你想在 你的ECMAScript实现 或 引擎（例如火狐的 SpiderMonkey 和 Chrome 的 V8）中实现标准兼容的语言特性，这将十分有用。

ECMAScript 文档并不是旨在帮助脚本程序员；编写脚本时请参考  JavaScript 文档。

ECMAScript 规范 使用的术语和语法 对于一个 JS 程序员来说有可能有些生疏。尽管在ECMAScript 中对于语言的描述有所不同，但语言本身是一样的。JavaScript支持ECMAScript规范中列出的所有功能。

JavaScript 文档中描述了适合 JavaScript 程序员 的信息。