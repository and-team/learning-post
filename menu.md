# Android menu

```java
<menu xmlns:android="http://schemas.android.com/apk/res/android" >
    <item android:id="@+id/action_logout" android:title="@string/menu_logout_label"></item>
</menu>
```

## item

#### android:showAsAction

#### onOptionsItemSelected

```java
@Override
public boolean onOptionsItemSelected(MenuItem item) {
	int itemId = item.getItemId();
	//...
}
```