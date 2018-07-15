1、
Javascript组成
	ECMAScript：javascript核心，解释器、翻译。
	DOM-Document Object Model。Document实际就是HTML。操作HTML的能力。
	BOM-Browser Object Model。window。
	
2、
判断变量类型的方法，比如：
var a=1;
alert(typeof a);//number、string、boolean、function、object、undefined

3、
var a = '12';
var b=parseInt(a);//字符串转换为数字。
类似函数：parseFloat，可以兼容parseInt的整数转换
异常：NaN-Not a Number 非数字。
NaN和NaN是不相等的。
isNaN(b);//判断是否变量b是NaN。
isNaN函数与parseInt函数的配合使用。

4、
==和===区别。
==,先类型转换，然后比较。支持隐式类型转换
===，不类型转换，直接比。全等。
var a=5;
var b='5';
alert(a==b);//true
alert(a===b);//false

5、
闭包和示例

6、
命名规范
js推荐匈牙利命名法，1）类型前缀；2）首字母大写；

7、
什么是真，什么是假？
真；true，非零数字，非空字符串，非空对象。
假：false，数字零，空字符串，空对象null，undefined。

8、
三种主流浏览器对DOM的支持情况：
FF：99%支持DOM标准
IE：IE6-8 10%支持DOM标准；IE9支持很大，几乎99%。
Chrome：60%支持DOM标准

9、
表格table标签的<tbody>，默认浏览器会自动添加。

10、
关于运动框架，基于运动基础2、分享到、淡入淡出，三个运动的示例，提取共同的代码流程和逻辑，即为运动框架。
	a、在开始运动时，关闭已有定时器
	b、把运动和停止隔开(if/else)

11、
事件冒泡
大多数情况是没用的，都需要被我们屏蔽。

12、
重构，面向过程重构为面向对象：
1）不能有函数嵌套，但可以有全局变量；
2）onload->构造函数；全局变量->属性；函数->方法；
3）改错，诸如：this、事件、闭包、传参；

13、
JSON对象，写法简单，但是不适合多个对象的场景。适用于程序中单例的情况。
构造函数+原型是更通常的对象方式。