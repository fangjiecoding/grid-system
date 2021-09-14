# -grid-system
栅格系统 英文为 Grid Systems，也有翻译为 网格系统。
定义：运用固定的格子，遵循一定的规则，进行页面的布局设计，使布局规范简洁有规则。以规则的网格阵列来指导和规范网页中的版面布局以及信息分布。网页栅格系统是从平面栅格系统中发展而来。1692年法国为提高印刷水平，以方格为设计基础，将一个印刷版面分成上千个小格，这就是最早的栅格雏形。再后来，慢慢演变成运用固定的格子设计版面的平面设计风格。不过对于网页设计来说，栅格系统的使用，不仅可以让网页的信息呈现更加美观易读，更具可用性。而且，对于前端开发来说，网页将更加的灵活与规范。

bootstrap栅格系统是一套响应式、移动设备优先的流式栅格系统，随着屏幕或视口（viewport）尺寸的增加，系统会自动分为最多12列栅格系统用于通过一系列的行（row）与列（column）的组合来创建页面布局
	
基础应用
	按照不同屏幕划分为12 等份
	行（row） 可以去除父容器作用15px的边距
	xs-extra small：超小； sm-small：小；  md-medium：中等； lg-large：大；
	列（column）大于 12，多余的“列（column）”所在的元素将被作为一个整体另起一行排列
	每一列默认有左右15像素的 padding
	可以同时为一列指定多个设备的类名，以便划分不同份数  例如 class="col-md-4 col-sm-6"
栅格嵌套
	栅格系统内置的栅格系统将内容再次嵌套
	可以通过添加一个新的 .row 元素和一系列 .col-sm-* 元素到已经存在的 .col-sm-*  元素内
列偏移
	使用 .col-md-offset-* 类可以将列向右侧偏移
		
列排序
	通过使用 .col-md-push-* 和 .col-md-pull-* 类就可以很容易的改变列（column）的顺序。
响应式工具
```              超小屏幕       小屏幕         桌面 (≥992px)  大屏幕
                手机 (<768px)  平板 (≥768px)  中等屏幕       桌面 (≥1200px)
.visible-xs-*	    可见	      隐藏	隐藏	隐藏
.visible-sm-*	    隐藏	      可见	隐藏	隐藏
.visible-md-*	    隐藏	      隐藏	可见	隐藏
.visible-lg-*	    隐藏	      隐藏	隐藏	可见
.hidden-xs	    隐藏	      可见	可见	可见
.hidden-sm	    可见	      隐藏	可见	可见
.hidden-md	    可见	      可见	隐藏	可见
.hidden-lg	    可见	      可见	可见	隐藏	
	

