# Maven Repositories
My Maven Repositories


1) Unzip into `C:\Users\ (your user name) \.m2\repository\`
2) You should have `com` folder under `\repository\`


In build.gradle file (project file) add:
````
buildscript {
  repositories {
    ...
    mavenLocal()
    ...
  }
  dependencies {
    ...
    classpath "com.bytedance.android:aabresguard-plugin:0.1.10"
    ...
  }
}
````
