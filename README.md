# DynamicSizes - dynamic scalable size unit

<p>An android SDK that provides a new size unit - hsdp. This size unit scales with the screen size. It can help Android developers with supporting multiple screens.</p>
Use it carefully! for example, in most cases you still need to design a different layout for tablets.
<p></p>
<div>
  <p align="center">Built with ❤︎ by
	  <a href="https://github.com/Hardik8184">Hardik Dungrani</a></p>
</div> 

## Demo
You can see that sdp scales with the screen size and the dp stays with the same size on all screen sizes.

## 💻 Installation & Requirements

For use this library, you should use **```AndroidX```** instead of **```Support```**

Add this in your app's build.gradle file(Using Android Studio and Gradle): 
  
  ```
  dependencies {
    implementation 'com.hardik.hsdp:scalablesize-android:1.0.1'
  }
  ```


## ❔ Usage & Example
**Basic Usage**

| Types | Values | Example |
|---|:---:| :---:|
| Normal sizes  | hsdp | _15hsdp |
| Font size  | font_ssp | _15font_ssp |
| Negative sizes  | mines_hsdp | _minus15hsdp |


**Basic Example**

How to use this hsdp size unit, please see this link :
 [hsdp_layout.xml](https://github.com/Hardik8184/DynamicScalableSize/blob/master/scalablesize-android/src/main/res/layout/hsdp_layout.xml)

# 📃 License

    Copyright 2019 Hardik Dungrani

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

### If you like the library, please click on the ★ Star button at the top 😊