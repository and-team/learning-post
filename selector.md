# Android selector 

```xml
//button_color.xml
<selector xmlns:android="http://schemas.android.com/apk/res/android">
</selector>	
```


#### 属性

* android:state_selected	选中
* android:state_focused		获得焦点
* android:state_pressed		点击
* android:state_enabled		


```xml
<selector xmlns:android="http://schemas.android.com/apk/res/android">
	<item android:state_selected="true" android:color="#fff" />
	<item android:state_focused="true" android:color="#fff" />
	<item android:state_pressed="true" android:color="#fff" />
	<item android:color="#000" />
</selector>
```

## 默认时候的背景图

在 drawable 目录下放一个 pic 文件

```xml
<item android:drawable="@drawable/pic" />
```

## 应用在按钮

```xml
<Button android:focusable="true"
		android:background="@drawable/button_color" />
```

