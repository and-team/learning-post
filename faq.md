# Android FAQ 
常见问题汇总

## 布局文件不可以有大写字母，only lowercase a-z,0-9,or _.

## sub packages

It allows us to organize our classes in a more meaningful way for how they are used.


## sdk 安装目录

mac 下：Library/Android/sdk

## 如何定义一个数组

```xml
String[] arr = {"zhang", "yao", "chun"};
```

## INSTALL_FAILED_OLDER_SDK 错误如何解决？

一般都是 manifest 文件里面有指定 

```xml
<uses-sdk android:minSdkVersion="4" />
```




## 扩展阅读

* [安装提示错误 [INSTALL_FAILED_OLDER_SDK]的解决方案](http://blog.csdn.net/jingwen3699/article/details/9793345)