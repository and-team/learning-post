# Android Service

后台运行一些事务的处理

## 创建

new 一个 service

自动在 manifest 里面生成：<application> 里面

```xml
<service
	android:name=".MyService"
	android:enabled="true"
	android:exported="true" >
</service>
```

## startService

```java
startService(new Intent(MainActivity.this, MyService.class));
```

## stopService

```java
stopService(new Intent(MainActivity.this, MyService.class));
```

## 生命周期

## 