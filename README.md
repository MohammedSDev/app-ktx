# app-ktx
![Release](https://jitpack.io/v/clickapps-android/app-ktx.svg)




App-ktx is an common extensions functions that try help you focus on bussines logic & leave rest usually stuff for it.
e.g set custom text font type, convert file to base64,change app language at runtime ,convert date string from/to any format,
calcluate time ago, convert dp to px,px to dp  ... and more..

# add dependence
in project level build.gradle

```gradle
allprojects {
  repositories {
                  google()
                  jcenter()
                    //...
                  maven { url 'https://jitpack.io' }
  }
}
```
in app level build.gradle
```gradle
dependencies {
        implementation 'com.github.clickapps-android:app-ktx:<last-build>'
}
```
# Enjoy using app-ktx library,report any bugs you found,request any update ,or even drop me an email gg.goo.mobile@gmail.com
