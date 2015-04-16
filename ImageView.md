# ImageView
ImageView相关的东西

直接继承自 View 类，主要用于图片显示。

## 常用属性

#### android:src 设置 ImageView 的图片来源

android:src="@drawable/main_title"

#### android:maxHeight

设置 ImageView 的最大高度

* 需要把 adjustViewBounds 设置为 true
* 需要设置 maxWidth
* layout_width 和 layout_height 都为 wrap_content

#### android.maxWidth

设置 ImageView 的最大高度

* 需要把 adjustViewBounds 设置为 true
* 需要设置 maxHeight
* layout_width 和 layout_height 都为 wrap_content

#### android:adjustViewBounds

是否保持宽高比，需要和 maxWidth 和 maxHeight 一起使用，单独无效


#### android.scaleType

* center        把图片放在 ImageView 中央，不进行任何缩放
* centerCrop    保持纵横比例缩放图片，使图片完全覆盖 ImageView
* centerInside  保持纵横比例缩放图片，使 ImageView 能完全显示图片
* fitEnd        保持纵横比例缩放图片，缩放完成后将图片放置在 ImageView 的右下角
* fitCenter		保持纵横比例缩放图片，缩放完成后将图片放置在 ImageView 的中央
* fitStart 		保持纵横比例缩放图片，缩放完成后将图片放置在 ImageView 的左上角
* fitXY			纵横向独立缩放，以铺满 ImageView
* matrix		使用 matrix 方式来缩放



## 扩展

* [Android ImageView图片自适应](http://blog.sina.com.cn/s/blog_618199e60100y537.html)
