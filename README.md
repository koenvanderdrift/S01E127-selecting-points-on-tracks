# Swift Talk
## Map Routing: Selecting Points on Tracks

This is the code that accompanies Swift Talk Episode 127: [Map Routing: Selecting Points on Tracks](https://talk.objc.io/episodes/S01E127-selecting-points-on-tracks)


This fork allows gpx files other than the ones associated with the project to be loaded.

* Put the gpx files in a second folder, named _gpx2_, and add this to the project as a `Bundle Resource`.
* Make sure to call `load2()` from `viewDidLoad()` in the `ViewController`.
