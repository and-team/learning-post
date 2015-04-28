# AndroidManifest.xml 


## 是什么？

* 权限申请和定义配置的文件

## 功能：

* 声明 application 需要的 Android API 的最低版本级别
* 列举 application 需要的链接的库
* 声明 application 必须具备的权限，访问受保护的部分 API，以及和其他 application 交互
* 描述 application 的 component
* 包名是 application 的唯一标识


## 第一层：

1. xmlns:android

定义 android 的命名空间，一般是： http://schemas.android.com/apk/res/android

2. package

主程序的包名

## 第二层：

必须含有一个 application，声明每一个应用程序的组件及其属性。

1. android:icon  

整个 APP 的图标

2. android:theme

资源的风格，定义了一个默认风格给所有的 activity


## 第三层：

activity 


## 第四层：

intent-filter

1. action

一个 intent-filter 至少应该包含一个 action。

只有 android:name 这个属性。比如：android.intent.action.MAIN，表示此 activity 是作为应用程序的入口

2. category

只有 android:name 这个属性。比如：android.intent.category.LAUNCHER，表示应用程序是否显示在程序列表里面。



#### uses-permission

* [连网](http://developer.android.com/training/basics/network-ops/connecting.html)

```xml
<uses-permission android:name="android.permission.INTERNET" />
```


* 获取 GPS 定位相关的

```xml
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
```

* 读取手机当前的状态

```xml
<uses-permission android:name="android.permission.READ_PHONE_STATE" />
```

* 用于访问 wifi 网络信息，获取当前 wifi 接入的状态

```xml
<uses-permission android:name="android.permission.ACCESS_WIFI_STATE" />
```

* 向扩展卡里面写入数据

<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />


* 拨打电话

<uses-permission android:name="android.permission.CALL_PHONE" />


## 扩展阅读：

* [What permission do I need to access Internet from an android application?](http://stackoverflow.com/questions/2378607/what-permission-do-i-need-to-access-internet-from-an-android-application)
* [android权限](http://blog.sina.com.cn/s/blog_4ba5b45e0102ek9m.html)
* [Android声明和使用权限](http://blog.csdn.net/liuhe688/article/details/6417983)
* [Android permission 访问权限大全](http://www.cnblogs.com/wservices/archive/2010/05/04/1727250.html)