# flutter_naverlogin_plugin

네이버아이디로그인_plugin

## setting해야할것

strings.xml 에서
```<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="client_id">***</string>
    <string name="client_secret">***</string>
    <string name="client_name">flutter_naverlogin</string>
</resources>
```
AndroidManifest.xml에서

```<application
        android:name="io.flutter.app.FlutterApplication"
        android:label="flutter_naverlogin"
        android:icon="@mipmap/ic_launcher">
        <meta-data
            android:name="com.naver.sdk.clientId"
            android:value="@string/client_id" />
        <meta-data
            android:name="com.naver.sdk.clientSecret"
            android:value="@string/client_secret" />
        <meta-data
            android:name="com.naver.sdk.clientName"
            android:value="@string/client_name" />
```
