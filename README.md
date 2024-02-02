# Reproduction app for issue with AspectFill on Android

This app reproduces a bug on version 1.0.6 for the package [FFImageLoading.Maui](https://github.com/microspaze/FFImageLoading.Maui).
Setting `Aspect="AspectFill"` on Android for `CachedImage` controls does not work as expected. This is working normally on iOS and works on both platforms with the Maui `Image` control.

The issue on GitHub is: 