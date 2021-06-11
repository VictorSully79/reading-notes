# Filters
#### notes taken from: https://developer.android.com/training/basics/intents/filters

## Allowing Other Apps to Start Your Activity
### Ensure if your app can be useful to another you use `ACTION_SENT` intent.
### Intent Filters:
- Action: Names the action to perform i.e `ACTION_SEND` or `ACTION_VIEW` among others.
- Data: `<data>` gives the description of the data to be sent.
- Category: `CATEGORY_DEFAULT` Provides an additional way to characterize the activity

### Each incoming intent specifies only one action and one data type, but it's OK to declare multiple instances of the `<action>`, `<category>`, and `<data>` elements in each `<intent-filter>`.

### Handle the Intent:
- As your activity starts, call `getIntent()` to retrieve the Intent that started the activity. You can do so at any time during the lifecycle of the activity, but you should generally do so during early callbacks such as `onCreate()` or `onStart()`.

### Finally return the result to the activity that invoked yours with `setResult()` and `finish()`