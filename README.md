# 5MinuteSpeedometer
5 Minute Speedometer

How to make quick 5 min speedometer in Android studio
Code is on github: https://github.com/dbojan/5MinuteSpeedometer

Based on 5 Minute Android Speedometer ( https://www.youtube.com/watch?v=bYiOdw4mDnQ&t=622s ), and some parts from 
Develop Simple Speedometer in Android Studio ( https://www.youtube.com/watch?v=tRTX7Jere6E , Interesting stuff starts around 17 minute, iBaseGpsListener will be deleted!).

You can also download android gps apps projects for Android studio from github:
https://github.com/Mercandj/speedometer
https://github.com/mypapit/speedometer-android

Basically you have to ask user for fine location (gps) permission, because of the changes in android 6.

The easiest way for this to work in Android Studio is to add this in main activity:
ActivityCompat.requestPermissions(this,new String[]{Manifest.permission.ACCESS_FINE_LOCATION}, 1);

For more info on Fine location permissions in Android 6: 
https://stackoverflow.com/questions/33865445/gps-location-provider-requires-access-fine-location-permission-for-android-6-0/33866959.

Infromation on requestLocationUpdates:
https://developer.android.com/reference/android/location/LocationManager.html#requestLocationUpdates(long,%20float,%20android.location.Criteria,%20android.app.PendingIntent)


Longer way is described in this video: https://youtu.be/ua4jY0lBvCA
