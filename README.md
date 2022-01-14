# RoundImage
圆角图片

## **1、导入**
 1.引入jitpack
 ```java
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
2.添加
```java
implementation 'com.github.summersrest:RoundImage:v1.0.0'
```
## **2、使用**
### 1、xml中使用
```xml
<com.sum.round_image.RoundedImageView
        app:riv_oval="true"
        android:scaleType="centerCrop"
        android:src="@mipmap/image"
        android:layout_width="100dp"
        android:layout_height="100dp"/>
```


