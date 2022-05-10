# kor-standout
The kor standout library is based on the Standout library by Mark Wei letting you easily create floating windows in your android app. 

# Android support
we improved on the code to support higher modern sdks

```
 compileSdk 32

    defaultConfig {
        minSdk 23
        targetSdk 32
        multiDexEnabled true
    }
```

# Implement the library

<p>Step 1. Add it in your root build.gradle at the end of repositories:</p>

```

allprojects {
	repositories {
		maven { url 'https://jitpack.io' }
	}
}
 
```

<p>Step 2. Add the dependency</p>

```

dependencies {   
  implementation 'com.github.bhaaee:kor:-SNAPSHOT'
}

```

***Screenshots:***

<img src="https://raw.githubusercontent.com/bhaaee/observer-standout/main/bhaee%20net%20(1).PNG" height="400"/><img src="https://raw.githubusercontent.com/bhaaee/observer-standout/main/bhaee%20net%20(2).PNG" height="400"/><img src="https://raw.githubusercontent.com/bhaaee/observer-standout/main/bhaee%20net%20(3).PNG" height="400"/><img src="https://raw.githubusercontent.com/bhaaee/observer-standout/main/bhaee%20net%20(4).PNG" height="400"/>


