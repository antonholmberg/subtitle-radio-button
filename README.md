[![](https://jitpack.io/v/540Grunkspin/SubtitleRadioButton.svg)](https://jitpack.io/#540Grunkspin/SubtitleRadioButton)

# Subtitle Radio Button

Simple radio button with an additional subtitle.

## Usage

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:orientation="vertical">
    <org.grunkspin.subtitleradiobutton.SubtitleRadioButton
        app:titleText="Title"
        app:titleTextAppearance="@style/TextAppearance.AppCompat.Body2"
        app:subtitleText="Subtitle"
        app:subtitleTextAppearance="@style/TextAppearance.AppCompat.Body1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
</LinearLayout>
```

It uses the text internally so setting text will override the title and subtitle.