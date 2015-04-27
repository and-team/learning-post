# Android selector 

```xml
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

