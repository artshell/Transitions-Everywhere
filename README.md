Transitions Everywhere
============
Backport of [Transitions API from Android KitKat and Lollipop][1]. Compatible with <b>Android 2.2+</b>.

About Transitions API
============
[Video - DevBytes: Android 4.4 Transitions][2]<br>
[Sample project from Google][3] 

Versions info
============
<b>1.1.0</b>
- Port of new transitions from <b>Android 5.0 Lolipop</b> (but some work are still in progress)
- Package name changed from `android.support.transition` to `android.transitions.everywhere`!

Simple example
============
<img src="http://www.doubleencore.com/wp-content/uploads/2013/11/transitionSample.gif"/>

Usage
============
Gradle:
```
dependencies {
    compile "com.github.andkulikov:transitions-everywhere:1.1.0"
}
```
Use transition classes from package `android.transitions.everywhere.*` instead of `android.transition.*` from 4.4 and 5.0 Transitions API.<br>
If you use XML files to create your transitions you need to put them in the res/anim folder instead of the res/transition folder.

About library
============
Transition animations backported to <b>Android 3.0</b>.<br>
For Android ver. <b>>= 2.2</b> and < <b>3.0</b> scene to scene (layout to layout) changes is executed by the same API  but without animations.

<b>Note:</b> some of transitions classes was marked as hidden by developers of Android. You can find it in package  `android.transitions.everywhere.hidden`. But i don't recommend to use them because they can work unstable.

Thanks to github users: <b>[pardom][4]</b> and <b>[guerwan][5]</b>  

[1]: http://developer.android.com/reference/android/transition/package-summary.html
[2]: https://www.youtube.com/watch?v=S3H7nJ4QaD8
[3]: https://developer.android.com/samples/BasicTransition/index.html
[4]: https://github.com/pardom/TransitionSupportLibrary
[5]: https://github.com/guerwan/TransitionsBackport

<br>
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-transitions--everywhere-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/1050)
