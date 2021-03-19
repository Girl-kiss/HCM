### target
+ 可以取值：iframe或者frame（页面中的窗口）的name值x target =“x”
           表示：在指定的框架内打开\
+ name属性：URL的参数名称（后台服务器会根据这个名称来获取搜集数据）
+ 单选按钮必须设置value属性
+ 默认被选中checked属性只要存在就表示默认被选中
+ 多选框：name属性可以可以不一致
+ 素材网站：http://www.pzhuweb.cn/program/website.html
+ hidden:1.默认值
         2. 将不可用的数据（用户可见但不可用disabled）传递给服务器
###  表单控件
+ input（10种 单标记  <input />）
+ 其他的信息收集控件
### 其他控件
+    <textarea>可以存放文本框默认里面的值<textarea />
+    style 调整框是否框拉大
+ 下拉列表 select
    + 默认个数是 1
+ button
    + <button>  按钮双标签 </button>（如果在表单中，单击后自动触发sumit）
	+ 表单之外，他就没有效果。
	+ 成对标签，修改按钮上的文字
### 块元素和行元素
+ 块元素：独占一行  p  h1 （能设置宽度）
+ 行内元素： 共用一行  a （不能设置宽度）
+ 行内块元素： img 可以共用一行，可以共用宽度·
+ div（块元素）  span （行内元素）
### 滚动标签
+ <marquee> 滚动标签 </marquee>
    + 属性： 速度 scrollamount
	         滚动方向 direction 
			 左右晃动 behavior =“alternate”
### 其他重要的属性
### 框架
+ 浮动框架 iframe
     + 嵌入到页面的子页面
	 + src  用来连接他的资源
	 + width
	 + height
+ frameset   (set  集合的意思)
     + 不能和body同时使用  
	 + rows （拆分的方向和比例  rows="20%","80%"）
	 + clos
	 + 在这个标签中可以直接使用frame或frameset
### CSS
+ 定义：层叠样式表
+ 层叠 1.样式表中的样式叠加 2.同一元素的多种样式会发生继承和覆盖
+ 样式
+ 表
####CSS的样式表分类
+ 外部样式（用link标签   <link  href="连接CSS样式文件" rel="" type="text/css"/>）
   +        将样式保存在*.css文件中
+ 内部样式  <style></style>在head中使用
+ 行内样式  在标签中使用style标签
#### CSS 样式（重点）
+ 语法：
      选择器 {
	      属性:属性值;
          属性:属性值;
          属性:属性值;
		  }
+ 为什么？
   + 将内容和显示分离，加快烟网页显示速度
   + 易维护，提高工作效率
   + 易扩展
   + 可移植，可重用
### 样式的优先级
+ 行内样式（标签>内部样式（网页）>外部样式>（外部CSS文件）>浏览器的默认样式）   
## 其他语法
+ /*  */
+ 

																																																																																																																																																																																																																																																																																																																																																																						+ 

			 










