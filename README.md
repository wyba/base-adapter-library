# base-adapter-library

Add it in your root build.gradle at the end of repositories:

Step 1. Add the JitPack repository to your build file

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


Step 2. Add the dependency

	dependencies {
	        compile 'com.github.wyba:base-adapter-library:V1.0.0'
	}