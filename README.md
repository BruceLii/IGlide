# iglide
glide imitation project

模拟Glide 的生命周期管理，和图片的三级缓存。

#how to  reference this
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.BruceLii:iglide:v1.0.0'
	}
