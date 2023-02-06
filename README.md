# HERE SDK Routing Polyline Customization Example

Modified based on [HERE SDK 4.x - Navigation Example for Android](https://github.com/heremaps/here-sdk-examples/tree/master/examples/latest/navigate/android/Routing).

Demonstrating how to customize routing polyline for showing toll road and non-toll road in different colors by referring to [Span.getCarAttributes](https://developer.here.com/documentation/android-sdk-navigate/4.13.1.0/api_reference/com/here/sdk/routing/Span.html#getCarAttributes()).

---

The Routing example app shows how to calculate a route from A to B with a number of waypoints in between that is visualized on the map. You can find how this is done in [RoutingExample.java](app/src/main/java/com/here/routing/RoutingExample.java).

Build instructions:
-------------------

1) Copy the AAR file of the HERE SDK for Android to your app's `app/libs` folder.

Note: If your AAR version is different than the version shown in the _Developer's Guide_, you may need to adapt the source code of the example app.

2) Open Android Studio and sync the project.

Please do not forget: To run the app, you need to add your HERE SDK credentials to the `MainActivity.java` file. More information can be found in the _Get Started_ section of the _Developer's Guide_.
