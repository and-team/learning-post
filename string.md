# Java String 
记录一些和 Java String 有关的东西

## getString

## format

## trim

## isEmpty

## startsWith

## toLowerCase

## toUpperCase


## equals 与 equalsIgnoreCase

* equals: 两个字符串具有相同的字符和长度，返回 true，区分大小写
* equalsIgnoreCase: 忽略大小写比较


```java
String name = "zhangyaochun";
String name2 = "ZHANGYAOCHUN";
"zhangyaochun".equals(name);   //true
"zhangyaochun".equals(name2);  //false 
"zhangyaochun".equalsIgnoreCase(name2);  //true 
```


## StringBuilder