# ZED Monokai Themes Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a
Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres
to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## Unreleased
(None)

## 1.1.0 2023-02-03
### Changed
- Make "UI" improvements to `Monokai`
    - Darker background.
    - Gutter Slightly lighter than background.
    - Improve search match background (lighter, grayer).
    - Improve editor.active_line.background and make it semi-transparent.
    - Adopt the same `players` styles as `Atelier Cave Dark`.
        - It turns out that these styles drive the cursor and selection color for multiple users. The default single-user selection colors wasn't great for `Monokai` (it was too dark).  I don't know how to test all the multi-user colors well, but they look good in principle and `Monokai` is similar enough to `Atelier Cave Dark` that they should play well here.

## 1.0.0 2023-02-03
Initial Release