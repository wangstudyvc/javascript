1、
CSS的使用方式：
    1）浏览器缺省设置，我们将其清除；
    2）外部样式表；强烈建议的方式。
    3）内部样式表:缺点是会导致页面加载比较慢。
    4）内联样式表；
    5）导入样式表：在样式表中include其他样式表。
        @import url(css.css);

2、
选择符
分组选择符，比如：p,h1 {...}，通过逗号组成一组进行选择。
通配选择符，比如：* {}。
包含选择符，比如：ul li{}或ul>li{}
选择器用法生效时的优先级。优先级遵循就近原则，但是!important是破例，优先级最高。
类选择器->标签选择器->统配选择符。

3、
CSS字体属性：
text-decoration：用于字体修饰，比如：删除线、下划线等。
line-height:字体行高。
text-shadow:字体阴影。

4、
CSS文本属性：
text-indent:文本缩进，值可以时px或%。
text-align:文本对齐方式。居左、居中、居右。

5、
CSS背景属性：
background-image：背景图片，默认时平铺。通过background-repeat可以取消默认。
background-attachment:背景浮动，即图片跟随滚动条滚动fixed或不跟随滚动scroll/local。
CSS加载图片的优化：减少网络图片请求的次数。比如多个图片，需要多次请求获取。通过background-position技术，可将由多个图片组成的一张大图中提取所需的小图，所以只要网络请求一张大图即可，这样请求数即可优化为一次。
background-postion：从一张大图中提取给定坐标的区域。
background可以综合以前background前缀的属性，简写方式，也是一种优化。

6、
每个HTML标签可以拥有多个类属性，从而可以接受多个类样式。class="a b c"

7、
定位属性:position和left\right\top\bottom。
参考：CSS定位示例.html和CSS定位示例-浮动属性.html

8、
盒子模型
外边距,margin简写形式:
margin 10px 15px 20px 25px //按顺时针方向，上右下左
margin 10px 20px //上下 左右
边框，border属性也支持border-top、border-right、border-bottom、border-left。
内边距，padding写法，完全类似margin。

9、
列表属性，用于<li>标签上。
list-style-type,list-stype-image
list-stype是综合属性的简写形式。
