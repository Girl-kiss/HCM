### 补充知识
+ target
取值：iframe或者frame（页面中的窗口）的name值 x target="x"
  表示：在指定的框架内打开\
+ name属性：URL的参数名字（后台服务器会更根据这个名字来获取收集的数据）
+ 单选按钮必须设置value值
+ 默认被选中checked="checked"（只要checked属性存在就表示默认选中）
+ 多选框：name属性可以不一致
+ 素材网站：http://www.pzhuweb.cn/program/website.html
+ hidden:
	+ 1.默认值
	+ 2.将不可用的数据（用户可见但是不可维护disabled）传递给服务器

### 表单控件
+ input （10种）单标记  ```<input />```
+ 其他信息收集控件
### 其他控件
+ ```<textarea></textarea>```
	+ rows
	+ cols
	+ 在标签中间编辑默认值
+ 下拉列表 select
	+ size 默认是1
+ button 按钮
	+ 如果在表单中，单击之后会自动触发submit
	+ 在表单之外，他就没有效果
	+ 成对标签，修改按钮上的文字 
	```<button>按钮上的文字</button>```
### 块元素和行内元素
+ 块元素：独占一行 p h1 （可以设置宽度）
+ 行内元素: 共用一行 a （不能设置宽度）
+ 行内块元素:img 共用一行，设置宽度
+ div（块元素） span（行内元素）
### 滚动标签
### 其他重要属性
+ disabled 不可用（用户不能修改，服务器不可读，灰色）
+ readonly 只读（用户不能修改，服务器可读，没变化）