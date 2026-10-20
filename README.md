# Forgiveness Frames (Geode mod, GD 2.2081 / Geode 5.11.2)

You touch a hazard -> you survive as long as you've been hitting it for <= N ticks in a row (N = 1-8, in mod settings). One clean tick resets the counter.

## Get a .geode file (easiest: GitHub, no setup)
1. Make a new GitHub repo and upload everything in this folder (including the hidden `.github` folder).
2. Go to the repo's **Actions** tab and wait for "Build Geode Mod" to finish (~5-10 min).
3. Download the **Build Output** artifact, unzip it, and take `custom.forgiveness-frames.geode`.
4. Put it in your Geode mods folder (in GD: Geode menu -> folder icon at the bottom of the mods list), then restart GD.

## Build locally instead
Install the Geode CLI + SDK (https://docs.geode-sdk.org/getting-started/), then in this folder run:
    geode build
