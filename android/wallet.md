# Installation

```kts
    implementation("com.staq:wallet:2.1.0")

    maven {
        url = uri("https://repo.staq.io/repository/trustless-sdk/")
    }
```

```xml
    <uses-permission android:name="android.permission.INTERNET" />
    <activity
        android:name="com.walletstaq.StaqWalletActivity" android:exported="false" />
```

Add meta data to application

```xml
    <meta-data android:name="com.google.android.geo.API_KEY" android:value="your api key" />
```

# Usage

```kotlin
    val intent = Intent(activity, StaqWalletActivity::class.java)
    startActivity(intent)
```