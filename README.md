This sample works fine on Android and iOS, where if you leave the View that has the Pan gesture while panning, the gesture will continue, and if you happen to stop panning outside of the view, you get a Completed event.

On Windows, once you leave the view while panning that has the pan gesture attached, the gesture stops working, even if you reenter the view, and you never get Completed or Canceled events.

Expected behavior is to be consistent with Android and iOS.
