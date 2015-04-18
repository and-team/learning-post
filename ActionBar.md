# Android Log 
记录一些和 log 有关的东西

android.util.Log 的类

有 2 个参数：

1. tag，一般传入当前的类名，用于对打印信息的过滤
2. msg，打印的具体内容

## Log.d(String tag, String msg)

Debug，应当只存在开发中

## Log.i(String tag, String msg)

Info

## Log.v(String tag, String msg)

Verbose

## Log.e(String tag, String msg)

Error