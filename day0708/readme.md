### 选择器
+ 选择网页元素（html）
+ 通过什么条件来选择网页元素（选择器）
### 常用选择器[必须掌握 4个]
1. *通配符 表示网页中的所有元素 应用：清除浏览器的默认样式
2. E类型选择器 eg:网页的标签 p img
3. #idname 通过id属性的值来选择（唯一） 优：简洁；缺：可用性比较低
4. .class选择器 不唯一
[扩展]网页中字体默认大小16px
大小的单位：px像素 em相对于汉字的大小 2em
### 组合选择器6个
+ E#id 不仅选中的元素是E而且id必须一致(不使用)
1. E.class 【常用】并
2. E,F 或
3. E F 空格 后代选择器（选中的是F，F是E的后代）
4. E>F 大于符号 父子选择器 （选中的是F，F是E的儿子）
5. E+F 选中的F，F是E的兄弟，并且E是F的上一个兄弟
6. E~F 通用兄弟选择器 F只要是E的弟弟就可以了
### 属性选择器7个（选中具有某个属性的标签）
1. E[foo] 只要有foo属性的E元素就可以了
2. E[foo="value"]
3. E[foo|="a-b-c"] 选中具有foo属性，且值等于a或者b或者c……的
4. E[foo~="a b c"] 选中具有foo属性，且值等于a或者b或者c……的
5. E[foo^="a"] 选中具有foo属性,且值是以a开头
6. E[foo$="a"] 选中具有foo属性,且值是以a结尾
7. E[foo*="a"] 选中具有foo属性,且值包含a
应用：表单的输入控件中
### 链接伪类选择器(4个)爱love恨hate原则
1. :link 链接之前的样式
2. :visited 访问之后的样式
3. :hover 鼠标悬停[重点、常用]
4. :active 点击的一瞬间[激活的样式]
### 伪元素选择器
1. ::first-line
2. ::first-letter
3. ::after 清除浮动产生的问题[掌握]
4. ::before 给元素加边框[掌握]
5. ::selection 给选中的文本添加样式
6. ::placeholder 改变文本提示文字的样式
### 操作伪类选择器7个
1. :focus获得焦点[掌握]
2. :checked
3. :disabled
4. :read-only
5. :required 必须输入的控件
6. :empty 文本节点为空 [掌握]
7. :not(E) 不是E的元素
### 结构伪类选择器10个
1. E:first-child 第一个为E的子元素
2. E:last-child
3. E:only-child
4. E:nth-child(n) 第n个 扩展：2n偶数个 even偶数odd奇数
5. E:nth-last-child(n) 倒数第n个
6. E:fist-of-type 第一个指定类型的孩子
7. E:last-of-type
8. E:only-of-type
9. E:nth-of-type(n)
10. E:nth-last-of-type(n)
### 选择器优先级
1. !important
2. id选择器
3. class选择器
4. 类型选择器（标签选择器）
5. 伪元素选择器
#### 规则
id  class  类型（十位） 伪元素（个位）