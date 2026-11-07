# BKD patch releases

This repository distributes Morphe patch bundles and the metadata Morphe Manager reads. It does not contain the patch implementation or a patched APK.

Add this repository as a patch source in Morphe Manager:

`https://github.com/lemineralz/morphe-patches-release`

After each published release, the private build workflow mirrors the matching `patches-<version>.mpp` release asset and updates `patches-bundle.json` and `patches-list.json`. Stable metadata is on `main`; prerelease metadata is on `dev`. Release assets are published before their metadata is updated.
