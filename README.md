# dxvk-caches
[DXVK caches to reduce stuttering!](https://github.com/doitsujin/dxvk#state-cache)

Feel free to contribute caches of new games or for merge with existing ones
[here](https://github.com/begin-theadventure/dxvk-caches/issues/new) (.zip them before) or on [Discord](https://discord.gg/RsYQ4UPwth).

Files are hosted [here.](https://sam.nl.tab.digital/s/oZRKz5So2B8gbzY)

For merging and checking I'm using: [dxvk-cache-tool](https://github.com/DarkTigrus/dxvk-cache-tool)
## How to get:

To get all caches try [TUTORIAL](https://github.com/begin-theadventure/get-dxvk-caches/blob/main/script/TUTORIAL.md) or just ctrl+f->.dxvk-cache in x directory.
## How to use
Extract .tar.xz file to get .dxvk-cache->paste to x directory.
## Directories:

**Wine**:
next to .exe or specified path with env variable.

**Steam**: `/path/to/steamapps/shadercache/1237970/DXVK_state_cache` default is `~/.local/share/..` or next to .exe if shader pre-caching is turned off. 

To find out which ID corresponds to a particular game, simply search it on [Steam](https://store.steampowered.com/search/) (app/**ID**/name).
# Security
Read [dxvk/issues/764](https://github.com/doitsujin/dxvk/issues/764)

If you're concerned, use [dxvk-async](https://github.com/Sporif/dxvk-async) instead.
