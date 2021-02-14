# RetroArcher.database

This repository is a collection of video game posters. Maybe other items can be added here in the future such as fanart, music, etc.

To contribute please follow these guidelines.


# Poster Template - Games
All posters should be added in the `retroarcher_poster_template.psd`. This will make things easy to recreate if a format change occurs.

Each game should have a group layer folder inside the `Platform Images\<platform>` group layer.

The game group name should be the no-intro or redump name. Tags can be excluded except in the case where the image or logo is unique to a region.

Within the game group layer it is preferred to have an image and a clearlogo. These should be linked to the original file.

The image size area 0 to 1000 pixels in X and Y. The image can exceed this and will automatically be cropped.

A PSD is not really a file that easy to collaborate on, therefore I request that if you are making additions, please create a pull request relatively early so I know there are pending changes. Then continue making your adjustments.


# Poster Template - Platforms
Platforms are more difficult to add. Each platform will require several SVG and PNG images.

SVG images:
 - logo
 - console
 - game
 - consolegame
 - controller (optional)
 - controls (optional)
 - icon_empty (optional)
 - icon_full (optional)

PNG images (96 dpi):
 - band1 (50x180px)
 - band2 (50x180px)
 - band3 (50x180px)
 - band4 (50x180px)
 - consolegame (120px in Y)
 - controller (120px in Y)
 - logo (900px max X or 250px max Y)

Once the PNGs are ready, duplicate a platform group. Inside the group, right click each layer individually and "Convert to Smart Object".

Then right click each layer individually again, and click "Re-link to file", selecting the new file.

Adjust the position of each PNG according to the list below.
 - logo, center node X: 500px Y: 1156px
 - consolegame, left/middle node X: 30px Y 1407.5px
 - controller, right/middle node X: 970px Y 1407.5px
 - band1 (no re-adjustment needed)
 - band2 (no re-adjustment needed)
 - band3 (no re-adjustment needed)
 - band4 (no re-adjustment needed)


# Posters
All posters should be saved from the `retroarcher_poster_template.psd`.

The following layers groups should be enabled:
 - `Poster Frame`
 - `Platform Elements\<platform>`
 - `Backgrounds\retroarcher`
 - `Platform Images\<platform>\<game name>`

All other layer groups should be disabled.