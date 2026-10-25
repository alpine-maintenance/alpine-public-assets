# alpine-public-assets

**Public.** Files the office iMacs download during setup (Mosyle can't host files, and the
IT repo `alpine-maintenance/alpine-it` is private). Logos and wallpapers only.

**Never put a secret, a person's details or anything internal here.** Everyone can read this repo.

The iMac scripts check each file's SHA-256 before installing it, so changing a file here also
means updating the hash in the matching script in `alpine-it`.

## wallpapers/

Alpine logo on Hub's colours, 5120x2880 (iMac 5K):

| File | Background |
|---|---|
| `alpine-green-5120x2880.png` | Logo green `#1d5e2f` (the default, set by Mosyle's Wallpaper profile) |
| `alpine-cream-5120x2880.png` | Hub light background `#f1eadc`, green script |
| `alpine-charcoal-5120x2880.png` | Hub dark cards/sidebar `#1f1f1f`, cream script |
| `alpine-black-5120x2880.png` | Hub dark background `#0f0f0f`, cream script |
