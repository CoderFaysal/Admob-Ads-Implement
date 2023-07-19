# Admob Ads Implement


## Build Gradle
```
implementation 'com.google.android.gms:play-services-ads:22.2.0'
```


## Manifest
```
<!-- Sample AdMob app ID: ca-app-pub-3940256099942544~3347511713 -->
<meta-data
  android:name="com.google.android.gms.ads.APPLICATION_ID"
  android:value="ca-app-pub-3940256099942544~3347511713"/>
```


## BANNER Ads 

### XML
```
<LinearLayout
        android:id="@+id/banner"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentTop="true"
        android:layout_marginBottom="10dp"
        android:orientation="vertical"
        android:layout_marginTop="5dp"
        />

    <View
        android:id="@+id/divider"
        android:layout_width="wrap_content"
        android:layout_height="1dp"
        android:background="#E1E0E0"
        android:layout_below="@id/banner"
        />
```


### Java

```
Admob.setBanner(findViewById(R.id.banner), this);
```



