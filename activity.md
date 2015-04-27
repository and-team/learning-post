# Android Activity 

extends ContextThemeWrapper

## 生命周期

下图来自官网，充分地展现了整个周期：

<img src="activity.gif" />

## 状态

1. 激活或者运行，运行在前台（当前 Activity 栈的栈顶）
2. 暂停，失去焦点但是仍然对用户可见，比如：有其他 Activity 在它之上，或者透明或者没有遮住整个屏幕
3. 停止，被其他 Activity 覆盖

> 所有方法都必须先调用其父类的方法

#### onCreate

必须，初始化 Activity 的状态


## launchMode

在 AndroidManifest.xml 中配置了 activity 的 android:launchMode 

* standard			默认的启动模式
* singleTop			当前栈只有一个实例，按后退就退出了
* singleTask
* singleInstance





## 扩展阅读

* [官网的 Activity](http://developer.android.com/reference/android/app/Activity.html)
* [基础总结篇之二：Activity的四种launchMode](http://blog.csdn.net/liuhe688/article/details/6754323/)