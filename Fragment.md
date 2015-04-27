# Fragment
Fragment 相关的东西

3.0 引入的，翻译为碎片或者片段。为了解决不同分辨率的动态和灵活 UI 设计。

* 如果 3.0 之前的系统，需要导入 android-support-v4
* Fragment 必须嵌入在 Activity 中使用

```xml
public class AnotherFragment extends android.support.v4.app.Fragment {
	
}
```

## 生命周期

<img src="fragment_lifecycle.png" />

## onCreateView

```java
public View onCreateView(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState) {
	
}
```

onCreateView 返回一个 layout 对象，你可以从 layout.xml 中的某个对应 xml 生成对象。

## inflate()


```java
public View onCreateView(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState) {
	//...
	View root = inflater.inflate(R.layout.fragment_another, container, false);

	return root;
}
```

三个参数：

1、layout ID
2、存放 fragment 的 layout 的 ViewGroup
3、Boolean 类型的值，是否在创建 fragment 的 layout，把 layout 附加到 container 上，如果系统上已经把 layout 插入 container 中了，所以值 false。



## getFragmentManager

获取 FragmentManager，v4 中， getSupportFragmentManager

## transaction.add()

往 Activity 中添加一个 Fragment

## transaction.remove()

从 Activity 中移除一个 Fragment

## transaction.replace()

使用另一个 Fragment 替换当前的，就是 remove() 和 add() 的合体。









## DialogFragment



## 扩展阅读

* [Fragments in developer](http://developer.android.com/guide/components/fragments.html)
* [Android Fragments 详细使用](http://www.cnblogs.com/terryblog/archive/2012/02/17/2355753.html)