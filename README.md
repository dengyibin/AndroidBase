
[![](https://img.shields.io/badge/moven%20center-1.1.13-brightgreen.svg?style=flat)](https://bintray.com/betterliang/Android/appbase/1.1.13)
![](https://img.shields.io/badge/minSdk-15-blue.svg)
[![](https://img.shields.io/github/stars/lianghuiyong/AndroidBase.svg)](https://github.com/lianghuiyong/AndroidBase/stargazers)
[![](https://img.shields.io/github/forks/lianghuiyong/AndroidBase.svg)](https://github.com/lianghuiyong/AndroidBase/network)
# 项目开发基类

## Gradle

```gradle

    allprojects {
        repositories {
            jcenter()
            maven { url "https://jitpack.io" }
        }
    }

    android {
        dataBinding {
            enabled = true
        }
    }

    dependencies {
        compile 'com.better.android:appbase:1.1.13'
    }
```

## gradle-wrapper.properties

```gradle
distributionUrl=https\://services.gradle.org/distributions/gradle-3.3-all.zip
```


 [1、一些好用的基类](./readme/README_Base.md "一些好用的基类")
 
 [2、一个好用的列表页面基类](./readme/README_RecyclerView.md "一个好用的列表页面基类")
 
 [3、一些好用的资源](./readme/README_Resources.md "一些好用的资源")
 
 [4、常用的网络请求Code](./readme/README_ResponseCode.md "常用的网络请求Code")
 
 [5、一个常用的工具类包（来自AndroidUtilCode）](https://github.com/Blankj/AndroidUtilCode "一个常用的工具类包（来自AndroidUtilCode）")
 
 [6、基类页面或列表的网络提示](./readme/README_NetWork.md "网络提示")


## proguard-rules.pro

```gradle
-keep class com.chad.library.adapter.** {
   *;
}
```

## 附

 - [lambda配置](https://github.com/lianghuiyong/AndroidBase/wiki/lambda-%E9%85%8D%E7%BD%AE)

## 致谢
 
 - [![](https://img.shields.io/badge/OsChina%20App-2.8.0-brightgreen.svg)](http://git.oschina.net/oschina/android-app)
 - [![](https://img.shields.io/badge/RxJava-2.0-brightgreen.svg)](https://github.com/ReactiveX/RxJava)   
 - [![](https://img.shields.io/badge/butterknife-8.5.1-brightgreen.svg)](https://github.com/JakeWharton/butterknife)   
 - [![](https://img.shields.io/badge/todo-MVP-brightgreen.svg)](https://github.com/googlesamples/android-architecture/tree/todo-mvp/) 
 - [![](https://img.shields.io/badge/todo-DataBinding-brightgreen.svg)](https://github.com/googlesamples/android-architecture/tree/todo-databinding/) 
 - [![](https://img.shields.io/badge/BaseRecyclerViewAdapterHelper-2.9.0-brightgreen.svg)](https://github.com/CymChad/BaseRecyclerViewAdapterHelper) 
 