# Android Button 

Button extends TextView

> 默认 text 是大写的，可以设置 android:textAllCaps="false"


举例：

```xml
<Button
	android:layout_height="wrap_content"
	android:layout_width="wrap_content"
	android:text="Test by zhangyaochun"
	android:onClick="clickHandle" />
```

```activity
public void clickHandle(View view) {
	//..
}
```

其他几种





## ImageButton




## 扩展阅读

* [官网](http://developer.android.com/reference/android/widget/Button.html)