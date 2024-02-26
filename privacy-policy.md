# JExpense: Privacy Policy

## Data collected by the app
This app is designed to collect critical information which is financial information of the user. All data, including all of your setting such as search's options, is stored locally in your device only, and can be deleted by clearing the application's data or uninstalling the app. We didn't collect any of your data in the server.

## Explanation of permissions requested by the app
The following permissions are the real permissions specified inside `AndroidManifest.xml` and published.
All permissions listed below are used for functionality of the app which are export and import transactions' data as a CSV file. As mentioned above, these files stored locally in your device only. The main purpose of these files is for back-up data.

```xml
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.MANAGE_EXTERNAL_STORAGE"/>
```

| Permissions             | Reason                           |
|---------------------|----------------------------------|
| android.permission.WRITE_EXTERNAL_STORAGE     | Only affected devices that run API level 18 or lower. Need for writing CSV as an back-up file. |
| android.permission.READ_EXTERNAL_STORAGE     | Introduced in API level 19. Need for reading CSV as an import data function. |
| android.permission.MANAGE_EXTERNAL_STORAGE     | Same reason as android.permission.WRITE_EXTERNAL_STORAGE but for devices that run API level 19 or higher. |
