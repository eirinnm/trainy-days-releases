# Trainy Days releases

Firmware images and the OTA manifest for the private `trainy_days` repository.

The board reads `releases/latest/download/manifest.json` from here. The source
lives in the private repository; this one only holds the two files the device
needs, so no GitHub credential is stored on the board.

Do not edit releases by hand: `.github/workflows/release.yml` in the private
repository publishes them from a tag.