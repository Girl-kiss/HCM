### 表单
#### 表单的作用
+ 信息收集
+ 信息传给服务器
#### 表单的语法【重点】
+ form 表单标记
+ 重要的属性
    + action=“URI”
	+ method提交方式
	    + get
		+ post
		+ 区别【重点】
		    + 相对于get而言，post更安全（内容不会显示在地址栏），get会显示在地址栏
			+ get主动推送，速度更快，不需要考虑服务器状态
			+ get传输数据有长度的限制，post没有
			+ 默认是get提交方式
			+ 如果需要传输文件等特殊类型，必须使用post
    + 编码方式enctype
+ 补充
    + MIME（多用途互联网邮件扩展类型）
	+ 7种顶级类型
	   + 视频 video
	   + 图片 image
	   + 应用 application
	   + 文本 text
	   + 音频 audio
	   + 多部分媒体 multipart
	   + 报文信息 message
    + MIME格式 顶级类型/子类型
	+ 