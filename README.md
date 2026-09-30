# SampleUAMtoWeb

Unity 6 (6000.6.0f1) Web build of `Presentation_Room1`, a single-player showroom scene that streams a model from Unity Asset Manager (Unity Cloud DataStreaming, URP).

Live: https://jackstrongitharm.github.io/SampleUAMtoWeb/

- Controls: WASD to walk, hold right mouse to look, Shift to sprint. Touch controls toggle top-right.
- Auth: Unity Cloud Identity **Standard Login** (browser sign-in, then redirect back to this page).
- Build files are served uncompressed here, because GitHub Pages can't send the `Content-Encoding: br` header the original Brotli build needs.
