<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <!--COMPLETED (8) Wrap the TextView in a ScrollView-->
    <!--COMPLETED (9) Set the ScrollView width to match_parent and the height to wrap_content-->
    <ScrollView
        android:layout_width="match_parent"
        android:layout_height="wrap_content">

        <!--COMPLETED (2) Change the TextView's android:id attribute to tv_weather_data-->
        <!--COMPLETED (3) Give the TextView 16dp of padding-->
        <!--COMPLETED (4) Set the text size to 20sp-->
        <!--COMPLETED (5) Remove all attributes with the word constraint in them-->
        <!--COMPLETED (6) Remove the default text from the TextView-->
        <TextView
            android:id="@+id/tv_weather_data"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:padding="16dp"
            android:textSize="20sp" />
    </ScrollView>
</FrameLayout>
