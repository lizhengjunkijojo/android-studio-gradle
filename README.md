# android-studio-gradle
Android studio中配置使用Gradle

1.下载gradle-xxx-zip包，放置到android studio目录下，项目中配置参数

http://services.gradle.org/distributions



/Applications/Android Studio.app/Contents/gradle



distributionUrl=https\://services.gradle.org/distributions/gradle-2.13-all.zip

2.下载gradle-xxx-jar，放置到android studio目录下，项目中配置参数

https://jcenter.bintray.com/com/android/tools/build/gradle/



/Applications/Android Studio.app/Contents/gradle/m2repository/com/android/tools/build/gradle



dependencies {
    classpath 'com.android.tools.build:gradle:2.1.0’

}

3.
Mac上会默认下载到 /Users/<用户名>/.gradle/wrapper/dists 目录
Win平台会默认下载到 C:\Documents and Settings\<用户名>.gradle\wrapper\dists 目录
