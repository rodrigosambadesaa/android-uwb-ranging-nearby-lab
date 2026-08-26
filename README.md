# Android UWB Ranging / Nearby Lab

A hardware-aware Ultra-Wideband exercise using stable **AndroidX Core UWB 1.0.0** plus its RxJava3 bridge. The app:
- requests `UWB_RANGING`,
- creates a `UwbManager` only on capable/available devices,
- obtains a controlee session scope,
- builds `RangingParameters`, and
- subscribes to ranging result events.

The peer address in the demo is intentionally synthetic: successful ranging requires a second compatible device and out-of-band exchange of real session/channel data. On unsupported hardware the app reports the condition instead of crashing.
