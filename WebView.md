# Android WebView

```xml
<WebView android:layout_width="match_parent" 
		 android:layout_height="match_parent"
		 android:id="@+id/wv"></WebView>
```

```java
private WebView wv;

@Override
protected void onCreate(Bundle savedInstanceState) {
	//找到那个 xml 里的WebView
	wv = (WebView) findViewById(R.id.wv);
	wv.loadUrl("http://www.wandoujia.com");
}

```


## loadUrl

## reload

## setWebChromeClient