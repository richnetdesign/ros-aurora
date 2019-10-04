# AuroraStore and AuroraServices for RattlesnakeOS

Adapted from https://github.com/MSe1969/AuroraStore-prebuilt.
Apk files taken from https://gitlab.com/AuroraOSS/AuroraStore/-/tags.

## How to
Add the following to end of your `rattlesnakeos-stack` config file.
```
[[custom-prebuilts]]
modules = ["AuroraStore", "AuroraServices"]
repo = "https://gitlab.com/mgidding/aurora-store"
```
