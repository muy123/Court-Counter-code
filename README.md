# Court-Counter-code
match score card


<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="TEAM-A"
        android:layout_centerHorizontal="true"
        android:gravity="center_horizontal"
        android:padding="4dp"/>
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="0"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="14dp"
        android:gravity="center_horizontal"/>
    <Button
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="+3 POINTS"
        android:layout_margin="6dp"/>
    <Button
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="+2 POINTS"
        android:layout_margin="6dp"/>
    <Button
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="FREE THROW"
        android:layout_margin="6dp"/>


</LinearLayout>
