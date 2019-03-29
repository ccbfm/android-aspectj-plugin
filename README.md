# android-aspectj-plugin

buildscript {

    repositories {
    
        maven { url 'https://jitpack.io' }
	
    }
    dependencies {
    	
        classpath 'com.github.ccbfm:android-aspectj-plugin:1.0.0'
	
    }
}


引用插件：
apply plugin: 'ccbfm.android.aspectj.plugin'
