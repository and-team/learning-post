# Android Button 

Button extends TextView

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
