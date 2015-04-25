# Android Build 

```java
android.os.Build
```

## TIME

## TYPE

## USER

## BOARD

## MANUFACTURER

硬件制造商

#### isMeizu

public static final boolean isMeizu() {
	if (Build.MANUFACTURER.equalsIgnoreCase('meizu')) {
		return true;
	}
	return false;
}



## VERSION


#### CODENAME
#### INCREMENTAL
#### RELEASE
#### SDK_INT