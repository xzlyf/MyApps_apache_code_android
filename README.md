[![](https://jitpack.io/v/xzlyf/MyApps_apache_code_android.svg)](https://jitpack.io/#xzlyf/MyApps_apache_code_android)

# MyApps_apache_code_android
# 解决安卓使用不了Apache_code_Base64的问题
# 通过修改包名可以解决
# 该库为修改原库（apache_code)的任何类容，只修改了包名，向安卓兼容
# 该库仅供内部使用测试，请勿外传

```
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}

dependencies {
      implementation 'com.github.xzlyf:MyApps_apache_code_android:v1.0.0'
}

```
