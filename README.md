# mvn-repo
Maven Repositories


1) Unzip into C:\Users\(your user name)\.m2\repository\
2) You should have "com" folder under \repository\
3) In build.gradle file (project file):

  classpath "com.bytedance.android:aabresguard-plugin:0.1.10"

Add:

repositories {
  ...
  mavenLocal()
  ...
}
