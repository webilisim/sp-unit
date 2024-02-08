# SP UNIT - a scalable size unit for android
An android library that provides new size unit - (scalable sp). This size unit scales with the screen size. It can help to developers with supporting multiple screens. This library support screens from  300dpi to 1080dpi.

# Attention
Use it carefully! for example, in most cases you still need to design a different layout for tablets. But this library, already support to tablets. Just you should test and check it for every screen.

# Examples
[Here](https://github.com/webilisim/sp-unit/blob/main/sp-android/src/main/res/layout/sp_example.xml) is a single layout built using SP Unit
[And Here](https://github.com/webilisim/sp-unit/blob/main/sp-android/src/main/res/layout/dp_example.xml) is the same layout built using dp

# Getting Started

To add SP Unit to your project (Using Android Studio and Gradle): 

  add implementation 'com.intuit.sdp:sdp-android:1.1.0' to your build.gradle dependencies block.
  
  for example:
  
  ```
  dependencies {
    implementation 'com.github.webilisim:sp-unit:1.0.1'
  }
  ```
Check the [sp_example.xml](https://github.com/webilisim/sp-unit/blob/main/sp-android/src/main/res/layout/sp_example.xml) to see how to have to use this library.
