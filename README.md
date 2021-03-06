# Build your first app
The following pages teach you how to build a simple Android app. You’ll learn how to create a "Hello World" project with Android Studio and run it. Then, you'll create a new interface for the app that takes some user input and opens a second screen in the app.

But before you start, there are two fundamental concepts you should understand about Android apps:

-----------------------------------------------------------------------------------------------------
### Apps provide multiple entry points
Android apps are built as a combination of components that can be invoked individually. For example, an activity is a type of app component that provides a user interface.

The "main" activity is what starts when the user taps your app icon, but you can take the user straight into a different activity from other places, such as from a notification or even from a different app.

Other components such as broadcast receivers and services also allow your app to perform background tasks without a user interface.

After you build your first app, learn more about the other components at [App Fundamentals](https://developer.android.com/guide/components/fundamentals.html).

### Apps adapt to different devices
Android allows you to provide different resources for different devices. For example, you can create different layouts for different screen sizes. Then the system determines which layout to use based on the current device's screen size.

If any of your app's features need specific hardware, such as a camera, you can query whether the device has that hardware at runtime and then disable the corresponding features if not. You can also set some features as required so Google Play won't allow installation on devices without them.

After you build your first app, learn more about device configurations at [Device Compatibility](https://developer.android.com/guide/practices/compatibility.html).

-----------------------------------------------------------------------------------------------------

With those basic concepts in mind, click below to start building your first app! [Create an Android Project =>](https://developer.android.com/training/basics/firstapp/creating-project)
