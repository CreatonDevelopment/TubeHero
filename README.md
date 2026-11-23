# TubeHero

TubeHero is a controller-first YouTube client for retro handhelds. Download the installable ZIP from [Releases](https://github.com/CreatonDevelopment/TubeHero/releases/latest).

## Install on a TrimUI Brick Hammer

1. Check that the release lists your model and firmware. The current build targets stock Hammer firmware 1.1.1.
2. Extract the device ZIP at the root of the SD card. The app should be at `Apps/UTubeHero`.
3. Insert the card, open **Apps → TubeHero**, and connect to Wi-Fi.

## Publishing a release

After the tested device ZIP has been staged in the **candidate** draft, open **Actions → Publish release → Run workflow** on `main`. Choose **patch**, **minor**, or **major**. The workflow calculates the next stable version and publishes the staged build with its SHA-256 checksum.
