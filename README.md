# SquareLoading

[![](https://jitpack.io/v/yuweiguocn/SquareLoading.svg)](https://jitpack.io/#yuweiguocn/SquareLoading)

![](/art/square-loading-demo.gif)

## Design


![](/art/square-loading.gif)

Design by [Divan Raj](https://www.uplabs.com/desdivj) from [Animated Loader](https://www.uplabs.com/posts/animated-loader-after-effects-freebie)



## How to use
1.Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```
2.Add the dependency
```
	dependencies {
	        compile 'com.github.yuweiguocn:SquareLoading:v1.0.0'
	}
```
3.Add SquareLoading to you layout
```
<io.github.yuweiguocn.lib.squareloading.SquareLoading
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#E91E63"
        app:squareColor="@android:color/white"
        app:squareSize="12dp"
        app:squareCorner="2dp"
        app:dividerSize="2dp"
        app:xCount="4"
        app:yCount="3"
        />
```




## Contact me
weibo:[@于卫国](http://weibo.com/weiguo58)

gmail:[yuweiguocn@gmail.com](mailto:yuweiguocn@gmail.com)

blog:[yuweiguo's blog](http://yuweiguocn.github.io)

## License
```
Copyright 2016 yuweiguocn

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
