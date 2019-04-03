# android-aspectj-plugin

buildscript {

    repositories {
    
        maven { url 'https://jitpack.io' }
	
    }
    dependencies {
    	
        classpath 'com.github.ccbfm:android-aspectj-plugin:1.0.0'
	
	
	/**
	* Gradle 4.10.0 版本
     	* 解决WARNING: API ‘variant.getJavaCompile()’ is obsolete and has been replaced with
     	* ‘variant.getJavaCompileProvider()’ 使用：
     	*/ 
	
	classpath 'com.github.ccbfm:android-aspectj-plugin:1.0.1'
    }
}


引用插件：

apply plugin: 'ccbfm.android.aspectj.plugin'
