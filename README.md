# XuanRecyclerView
一个开源RecyclerView，支持添加head，伸缩head，下拉刷新，上拉加载，自定义空数据布局等。



# How to use
If you want use this library, you only have to download XuanRecyclerView project, import it into your workspace and add the project as a library in your android project settings.

If you prefer it, you can use the gradle dependency, you have to add these lines in your build.gradle file:

```xml
repositories {
    jcenter()
}

dependencies {
    compile 'com.github.navasmdc:MaterialDesign:1.5@aar'
}
```

# XML
Please consistent section ID
```xml
<android.support.v4.widget.SwipeRefreshLayout
    android:id="@+id/sw_layout"
    android:layout_width="match_parent"
    android:layout_height="wrap_content">
    
    <FrameLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <com.xuan.recyclerview.XuanRecyclerView
            android:id="@+id/recycler_view"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_marginTop="0dp" />

        <include
            android:id="@+id/recycler_empty_view"
            layout="@layout/recycler_empty_view" />
    </FrameLayout>
</android.support.v4.widget.SwipeRefreshLayout>
```

# Image
![Sample](https://github.com/soarcn/BottomSheet/blob/master/art/image.png?raw=true)
![Sample](https://github.com/soarcn/BottomSheet/blob/master/art/image1.png?raw=true)
![Sample](https://github.com/soarcn/BottomSheet/blob/master/art/image2.png?raw=true)
![Sample](https://github.com/soarcn/BottomSheet/blob/master/art/image3.png?raw=true)
![Sample](https://github.com/soarcn/BottomSheet/blob/master/art/image4.png?raw=true)
![Sample](https://github.com/soarcn/BottomSheet/blob/master/art/image5.png?raw=true)