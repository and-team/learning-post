# Android Launcher

## 快捷方式

桌面最基本的组件，用于直接启动某一个应用程序的某个组件（如 Activity、Service 等）。

#### 两种创建快捷方式：

1、在应用程序中构建一个 Intent，然后以 Broadcast 的形式通知 Launcher 创建一个快捷方式
2、为应用程序的组件注册一个符合特定条件的 IntentFilter，然后直接在 Launcher 添加启动该组件的快捷方式

## permission

创建和删除权限定义在 Manifest 中：

```xml
<uses-permission android:name="com.android.launcher.permission.INSTALL_SHORTCUT" />
<uses-permission android:name="com.android.launcher.permission.UNINSTALL_SHORTCUT" />
```


```xml
<uses-permission android:name="com.android.launcher.permission.CREATE_SHORTCUT" />
```






