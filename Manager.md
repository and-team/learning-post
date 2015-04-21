# Android Manager 

## PackageManager

#### 获取当前应用的版本号

## FragmentManager

## ConnectivityManager

#### 判断是否连网

```java
private boolean isNetworkAvailable() {
	ConnectivityManager manager = (ConnectivityManager) getSystemService(Context.CONNECTIVITY_SERVICE);

	NetworkInfo networkInfo = manager.getActiveNetworkInfo();

	boolean isAvailable = false;

	if (isAvailable != null && networkInfo.isConnected()) {
		isAvailable = true;
	}	

	return isAvailable;
}
```



## InputMethodManager

## RingtoneManager