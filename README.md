# DynamicSizes - dynamic scalable size unit

<p>An android SDK that provides a new size unit - hsdp. This size unit scales with the screen size. It can help Android developers with supporting multiple screens.</p>
Use it carefully! for example, in most cases you still need to design a different layout for tablets.
<p></p>
<div>
  <p align="center">Built with ❤︎ by
	  <a href="https://github.com/Hardik8184">Hardik Dungrani</a></p>
</div> 

# Example
You can see that sdp scales with the screen size and the dp stays with the same size on all screen sizes.

# Getting Started & Requirements

 Add dynamic scalable size to your project (Using Android Studio and Gradle): 
  
  ```
  dependencies {
    implementation 'com.hardik.hsdp:scalablesize-android:1.0.0'
  }
  ```

For use this library, you should use **```AndroidX```** instead of **```Support```**


## Usage & Example
| Types | Values | Example |
|---|:---:| :---:|
| Normal sizes  | hsdp | _15hsdp |
| Font size  | font_ssp | _15font_ssp |
| Negative sizes  | mines_hsdp | _minus15hsdp |


* For see more examples to see how to use to the hsdp size unit, please see this link :
 [hsdp_layout.xml](https://github.com/Hardik8184/Dynamic-Scalable-Size/blob/master/scalablesize-android/src/main/res/layout/hsdp_layout.xml)
