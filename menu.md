# Android menu

res/menu 下面的 xml

```java
<menu xmlns:android="http://schemas.android.com/apk/res/android" >
    <item android:id="@+id/action_logout" android:title="@string/menu_logout_label"></item>
</menu>
```

## item

#### android:showAsAction

* always

```xml

```

#### onOptionsItemSelected

```java
@Override
public boolean onOptionsItemSelected(MenuItem item) {
	int itemId = item.getItemId();
	//...
}
```