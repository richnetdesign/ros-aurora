# AuroraStore and AuroraServices for RattlesnakeOS

"Forked" from https://gitlab.com/mgidding/aurora-store.
Adapted from https://github.com/MSe1969/AuroraStore-prebuilt.
Apk files taken from https://gitlab.com/AuroraOSS/AuroraStore/-/tags and https://gitlab.com/AuroraOSS/AuroraServices/-/tags.

## How to
Add the following to end of your `rattlesnakeos-stack` config file.
```
[[custom-prebuilts]]
modules = ["AuroraStore", "AuroraServices"]
repo = "https://github.com/lephyrus/ros-aurora-store"
```
