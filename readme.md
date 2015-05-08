#Android Awesome Material

A library for Android that makes it super easy for developers to incorporate
material design and bootstrap themes into their apps. Includes three separate
font sets to chose from to for the icons; Font Awesome, Material Design Iconic
Font, and Pixeden Stroke Icon Font Set.

## Installation

#### 1. Download Repo

* includes all the values / assets / drawables for your ease of use


* gradle (need halp!)


You will **need** to include the following in any XML layouts that are going to be using AwesomeButtons or AwesomeText:

```
xmlns:awesome="http://schemas.android.com/apk/res-auto"
```

## Awesome Buttons

![Awesome Buttons](/screenshots/awesome_buttons.png?raw=true)

```xml
<cyd.awesome.material.AwesomeButton
    android:id="@+id/btnBootstrapPrimary"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Primary"
    android:layout_margin="10dp"
    android:padding="10dp"

    awesome:awesome_type="bootstrap_primary"
    awesome:awesome_icon_right="FA_HOME"
    awesome:awesome_icon_left="FA_HOME"
    awesome:awesome_icon="FA_HOME"
    awesome:awesome_font="font_awesome"
    awesome:awesome_rounded_corners="true"
    />
```

## Awesome TextViews

![Awesome Text](/screenshots/awesome_text.png?raw=true)


```xml
<cyd.awesome.material.AwesomeText
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textSize="60sp"
    android:textColor="@color/md_teal_500"
    android:layout_marginRight="10dp"
    awesome:awesome_font="material_design"
    awesome:awesome_icon="MD_HOME"/>
```


## Bonus Resources


* drawable file
* values
  * colors
  * rounded corners
* assets

### References

* Font Awesome - http://fortawesome.github.io/Font-Awesome/
* Material Design Iconic Font - http://zavoloklom.github.io/material-design-iconic-font/
* Pixeden - http://www.pixeden.com/icon-fonts/stroke-7-icon-font-set
* Material Design Colors - https://gist.github.com/daniellevass/b0b8cfa773488e138037
