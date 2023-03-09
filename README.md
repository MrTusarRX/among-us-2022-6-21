# among-us-2022-6-21



Permissions---->


//Overlay Permission (Add this under any uses-permission in Android manifest--->

<uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW"/>

//Service (Add this above application tag in Android Manifest)-->

/// <service android:name="com.android.support.Launcher" android:enabled="true"
    android:exported="false" android:stopWithTask="true" />
    
//Add this in MainActivity of Game below onCreate Method--->

invoke-static {p0}, Lcom/android/support/Main;->Start(Landroid/content/Context;)V
