# Welcome to the ChangeButtonOnTouch-Lib wiki!

## This lib was created to make custom buttons quickly; (Not working now)

With this lib, when the button is press, it change the text color and the button background / color.

### XML Example

       <com.example.onbutton.OnButton
        android:id="@+id/button2"
        android:layout_width="300dp"
        android:layout_height="75dp"
        
         android:background="@drawable/bg_button_rounded"
         app:onTouch_background="@drawable/bg_button_rounded2"
        
         android:textColor="#FFF"
         app:onTouch_text_color="#854"
        
        android:text="Button"
        /> 



The "**app:onTouch_background**" tag change the button background when press.
Use the tag "**android:background**" to set the background when the button is not press.


The "**app:onTouch_text_color="#854**" tag change the color Text in button when press.
Use the tag "**android:textColor**" to set the text color when the button is not press.


## Download

[Download](https://github.com/maonaparede/ChangeButtonOnTouch_0.1/releases/tag/v0.1) the .aar file and import in your project

And add in your "**build.gradle(:app)**"

    dependencies{

      implementation project(path: ':onbutton_0.1');

    }
