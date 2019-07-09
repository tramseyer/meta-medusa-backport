This is the repository of the backport specific Yocto layer for the Stromer Medusa hardware.

Patches:
- python3_3.7.2: Added python3-manifest-additions.json for defining more fine grained packages than python3-misc does.

Backports:
- [warrior: bluez 5.50](https://github.com/kraj/poky/commit/496a4f924d23df6beb9382b4e3bcdcf5c12a9cdf)
- [warrior: python3_3.7.2](https://github.com/kraj/poky/commit/e7710df480513db877cbb80d6e7d7789ab39377d)
- [warrior: opkg-utils](https://github.com/kraj/poky/commit/a79bc39033c07e5cb0aa5ca95afe8f035c403f33)

Fixed recipe version:
- [master: protobuf](https://github.com/openembedded/meta-openembedded/commit/2f5819d9c37387764a600d9dc8d22bee8a71f710)
- [master: python{,3}-protobuf](https://github.com/openembedded/meta-openembedded/commit/e78cf913076ba28633d0ec4540f15820a0d944d2)
