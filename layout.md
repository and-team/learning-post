# Android Layout 
记录一些和 layout 有关的东西

## LinearLayout

线性布局： android:orientation

* 水平 horizontal
* 垂直 vertical


#### android:gravity

设置该 view 里面的内容相对于该 View 的位置。


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

