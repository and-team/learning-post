# ImageView
ImageView相关的东西

直接继承自 View 类，主要用于图片显示。

## 常用属性

#### android:src 设置 ImageView 的图片来源

android:src="@drawable/main_title"

#### android:maxHeight

设置了 ImageView 的最大高度

#### android.maxWidth

设置了 ImageView 的最大高度


#### android.scaleType

* center        把图片放在 ImageView 中央，不进行任何缩放
* centerCrop    保持纵横比例缩放图片，使图片完全覆盖 ImageView
* centerInside  保持纵横比例缩放图片，使 ImageView 能完全显示图片
* fitEnd        保持纵横比例缩放图片，缩放完成后将图片放置在 ImageView 的右下角
* fitCenter		保持纵横比例缩放图片，缩放完成后将图片放置在 ImageView 的中央
* fitStart 		保持纵横比例缩放图片，缩放完成后将图片放置在 ImageView 的左上角
* fitXY			纵横向独立缩放，以铺满 ImageView
* matrix		使用 matrix 方式来缩放

