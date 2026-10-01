# SampleUAMtoWeb

Unity 6 (6000.6.0f1) Web build of `Presentation_Room1`, a single-player showroom scene that streams a model from Unity Asset Manager (Unity Cloud DataStreaming, URP).

Live: https://jackstrongitharm.github.io/SampleUAMtoWeb/

- Controls: WASD to walk, hold right mouse to look, Shift to sprint. Touch controls toggle top-right.
- Auth: **Sign in with Unity** panel (top-left). Unity's sign-in opens in a popup of the same browser and returns the code to `signin-callback.html`, so the app page stays loaded. Allow popups for this site if the browser blocks it. Session is in memory only (reload = sign in again).
- The popup flow cannot return a sign-in on play.unity.com (COOP header + third-party frame); plain hosts like this one work.
- Build files are served uncompressed here, because GitHub Pages can't send the `Content-Encoding: br` header the original Brotli build needs.
