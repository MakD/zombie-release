# zombie-release

## A theme for Jellyfin 10.9.x combining the best from the Public Themes

Huge Thanks to all the theme creators out there for their hard work. This theme takes bits and pieces from other themes, namely [Zesty](https://github.com/stpnwf/ZestyTheme/tree/main), [JellySkin](https://github.com/prayag17/JellySkin/tree/master), [Ultrachromic](https://github.com/CTalvio/Ultrachromic) and [JellyFin Landscape](https://github.com/krlsantcard/Jellyfin-10.9/tree/main). Please let me know in case I have missed out anybody.

Installation:

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@v5/zombie-min-git.css');
```

### Screenshots (Desktop)

Login:

![Login](https://github.com/MakD/zombie-release/blob/main/img/desktop/login.png)

Homepage:

![Homepage](https://github.com/MakD/zombie-release/blob/main/img/desktop/homepage.png)

Detail Page:

![Detail](https://github.com/MakD/zombie-release/blob/main/img/desktop/detail.png)

Movies Page:

![Movies](https://github.com/MakD/zombie-release/blob/main/img/desktop/movies.png)

Season Page:

![Series Season Page](https://github.com/MakD/zombie-release/blob/main/img/desktop/seasonpage.png)

Dashboard:

![Dashboard](https://github.com/MakD/zombie-release/blob/main/img/desktop/dashboard.png)

### Screenshots (Mobile)

![Mobile](https://github.com/MakD/zombie-release/blob/main/img/mobile/combined-mobile.png)

## Color Palettes

It's possible to change colour palettes. You can use the awesome ones provided by stpnwf in his [ZestyTheme Repo](https://github.com/stpnwf/ZestyTheme/tree/main), or the ones provided here. A custom palette is also possible.
Add the `@import url` below your main import.

### Palette 1

![Powder Blue](https://readme-swatches.vercel.app/ADDFF4) ![Slate Gray](https://readme-swatches.vercel.app/708090) ![Charcoal](https://readme-swatches.vercel.app/2F363B) ![Jet](https://readme-swatches.vercel.app/1C2124) ![Gunmetal](https://readme-swatches.vercel.app/3C464B) ![Dark Slate](https://readme-swatches.vercel.app/1D2629)

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-1.css');
```

## Palette 2

![Light Steel Blue](https://readme-swatches.vercel.app/A2CDEE) ![Dark Slate Gray](https://readme-swatches.vercel.app/5A686E) ![Onyx](https://readme-swatches.vercel.app/24292E) ![Eerie Black](https://readme-swatches.vercel.app/12171B) ![Outer Space](https://readme-swatches.vercel.app/333C42) ![Midnight](https://readme-swatches.vercel.app/1B2328)

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-2.css');
```

## Palette 3

![Sky Blue](https://readme-swatches.vercel.app/92C7E6) ![Slate Blue](https://readme-swatches.vercel.app/505C63) ![Space Gray](https://readme-swatches.vercel.app/282F34) ![Black Charcoal](https://readme-swatches.vercel.app/161B1F) ![Steel Gray](https://readme-swatches.vercel.app/384248) ![Graphite](https://readme-swatches.vercel.app/192227)

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-3.css');
```

## Palette 4

![Teal](https://readme-swatches.vercel.app/80CBC4) ![Storm Gray](https://readme-swatches.vercel.app/647C83) ![Gunmetal Gray](https://readme-swatches.vercel.app/2D3436) ![Jet Black](https://readme-swatches.vercel.app/191D1F) ![Dark Slate](https://readme-swatches.vercel.app/3C4749) ![Charcoal Gray](https://readme-swatches.vercel.app/162221)

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-4.css');
```

## Palette 5

![Aqua Blue](https://readme-swatches.vercel.app/78BED5) ![Smoky Gray](https://readme-swatches.vercel.app/5A696E) ![Carbon Gray](https://readme-swatches.vercel.app/262E32) ![Ebon](https://readme-swatches.vercel.app/151A1D) ![Granite](https://readme-swatches.vercel.app/364045) ![Iron Gray](https://readme-swatches.vercel.app/142024)

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-5.css');
```

## Palette 6

![Pale Blue](https://readme-swatches.vercel.app/6EB4C8) ![Cadet Gray](https://readme-swatches.vercel.app/4E5D64) ![Storm Cloud](https://readme-swatches.vercel.app/232B2F) ![Raven Black](https://readme-swatches.vercel.app/121719) ![Charcoal Blue](https://readme-swatches.vercel.app/323C41) ![Lead Gray](https://readme-swatches.vercel.app/131E22)

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-7.css');
```

## Palette 7

![Color1](https://readme-swatches.vercel.app/AAAAAA) ![Color2](https://readme-swatches.vercel.app/828282) ![Color3](https://readme-swatches.vercel.app/555555) ![Color4](https://readme-swatches.vercel.app/323232) ![Color5](https://readme-swatches.vercel.app/414141) ![Color6](https://readme-swatches.vercel.app/2D2D2D)

```
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-8.css');
```

# Get a featured bar at the top of your homepage

Firstly I would like to thank [BobHasNoSoul](https://github.com/BobHasNoSoul), and [SethBacon](https://forum.jellyfin.org/u-sethbacon) for making this possible. I tweaked my version, but the entire credits go to them.

## Pre-Requisites

1. Jellyfin UserID from the profile page.
2. Jellyfin API key

## Steps (Shutdown Jellyfin before proceeding)

1. Download the [slideshow.html](https://github.com/MakD/zombie-release/blob/main/spotlight-html/slideshow.html)
2. Enter your Jellyfin UserID and API key in lines 108 & 109 respectively and save it.
3. Create a folder `avatars` in your jellyfin-web folder.
4. Copy the slideshow.html file to the `avatars` folder.
5. Search for the file `home-html.RANDOMNUMBERS.chunk.js` in the jellyfin-web folder and open it.
6. Search for the line `data-backdroptype="movie,series,book">` and paste the following exactly after the `>`

```
<style>.featurediframe { width: 89vw; height: 300px; display: block; border: 1px solid #000; margin: 0 auto}</style> <iframe class="featurediframe" src="/web/avatars/slideshow.html"></iframe>
```

7. Save the file.
8. Add this to your customCSS in the admin dashboard (in case you using this theme, don't bother it's already added)

```
@media only screen and (max-device-width: 767px) {.featurediframe {height: 33vh !important;}}
```

9. Clear the cache of your browsers and reload. (Ctrl+f5 in chrome)
10. Profit.

This cycles randomly through your library. You can also specify a custom list to show as a spotlight. You can visit BoBHasNoSoul's repo for further steps.
