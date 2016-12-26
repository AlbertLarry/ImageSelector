# ImageSelector
图片选择并裁剪的库
## used
Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.AlbertLarry:ImageSelector:1.0'
	}

## introduce
	 ImageSelectorActivity.start(mActivity, 1, ImageSelectorActivity.MODE_SINGLE, true, true, true);

![](http://i.imgur.com/4sU6PCE.png)