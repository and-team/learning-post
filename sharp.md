# Android sharp

美化 UI 控件，自定义一些 UI.

> 几何形状，位置放置于 res/drawable 里面的 xml 

## android:shape

* rectangle	  矩形
* oval		  椭圆
* line		  水平直线	
* ring        环形

## size

大小

* android:width		---- 宽度
* android:height	---- 高度

## gradient

渐变

* android:startColor   ---- 起始颜色
* android:endColor	   ---- 结束颜色
* android:centerColor  ---- 中间颜色
* android:angle		   ---- 45 的整数倍，包括 0。0 is left to right, 90 is bottom to top
* android:type         ---- 渐变类型：linear、radial、sweep

## solid

填充，当设置填充颜色后，即使设置了渐变也没用~

* android:color        ---- 填充颜色


## corners

圆角

* android:radius
* android:topLeftRadius
* android:topRightRadius
* android:bottomLeftRadius
* android:bottomRightRadius


## stroke

描边

* android:width 		---- 描边宽度
* android:color 		---- 描边颜色
* android:dashWidth 	---- 虚线 - 的宽度，设置为 0 的化，就是实线
* android:dashGap		---- 虚线之间的间隔


## padding

布局的间隔

* android:left
* android:top
* android:right
* android:bottom
