# Android Layout 
记录一些和 layout 有关的东西

## LinearLayout

线性布局： android:orientation

* 水平 horizontal
* 垂直 vertical


#### android:gravity

设置该 view 里面的内容相对于该 View 的位置。


#### android:layout_gravity

设置该 view 相对于父 view 的位置


#### android:layout_weight

线性布局会根据该控件的 layout_weight 值与其所处布局中所有控件的 layout_weight 之和的比例为该控件分配占用的区域

比如：水平 LinearLayout 有 2 个按钮，它们的 layout_weight 都是1，则它们都拉伸到整个屏幕宽度的一半。



## RelativeLayout

相对布局

### 布局对齐属性：

#### android:layout_centerInparent

为 true 的时候，该控件被置于父控件的水平垂直居中

#### android:layout_centerVertical

为 true 的时候，该控件垂直居中

#### android:layout_centerHorizontal

为 true 的时候，该控件水平居中


#### android:layout_alignBaseline

该控件与 id 为 tv_account 的控件的基线对齐

```xml
android:layout_alignBaseline="@id/tv_account"
```




### 布局属性：

#### android:layout_below

该控件置于给定 id 为 tv_heard 的下面

```xml
android:layout_below="@id/tv_heard"
```


#### android:layout_toRightOf

该控件置于给定 id 为 tv_account 的右边

```xml
android:layout_toRightOf="@id/tv_account"
```
#### android:layout_above

和 上面的 layout_below 相反，该控件放置于 给定 ID 的上面。

#### android:layout_toLeftOf

和 上面的 layout_toRightOf 相反，该控件放置于 给定 ID 的左边。


## fill_parent 与 match_parent、wrap_content

* 他们都是 android:layout_width 和 android:layout_height 对应的值
* match_parent 会取代 fill_parent，将大小扩展到最大的宽度或者高度
* wrap_content 将控件的大小根据控件中的内容来分配，以 TextView 和 ImageView 为例，设置 wrap_content 将完全显示内部的文本和图像。会根据内容来更改大小。




## 扩展阅读：

* [【Android布局】在程序中设置android:gravity 和 android:layout_Gravity属性](http://blog.csdn.net/feng88724/article/details/6333809)