# Installation

```kts
    implementation("com.staq:wallet:2.11.0")

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
  val intent = Intent(activity, StaqWalletActivity::class.java).apply {
                putExtra("userId", "...")
                putExtra("secret", "...")
                // optional
                putExtra("mobile", "...")
                putExtra("email", "...")
            }
    startActivity(intent)
```


## Using Fragment
To embed wallet into fragment you can use `StaqWalletUiFragment`
```kotlin
    val childFragment = StaqWalletUiFragment()
    val args = Bundle().apply {
        putString("userId", "...")
        putString("secret", "...")
        // optional
        putString("mobile", "...")
        putString("email", "...")
    }
    childFragment.arguments = args

// Begin a transaction to add the ChildFragment to the container layout
childFragmentManager.beginTransaction()
    .replace(containerLayout.id, childFragment)
    .commit()
```

# Language
make sure you set the language using this method, so that the sdk can capture it
```kotlin
val appLocale: LocaleListCompat = LocaleListCompat.forLanguageTags("ar-Ar")
AppCompatDelegate.setApplicationLocales(appLocale)
```
