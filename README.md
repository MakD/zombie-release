# Zombie

![jsDelivr hits (GitHub)](https://img.shields.io/jsdelivr/gh/hm/makd/zombie-release?style=for-the-badge&logo=css&logoColor=white&labelColor=663399&color=000000&cacheSeconds=3600)

A CSS theme for Jellyfin 12 with an AMOLED black base, built for desktop, phones and tablets in both orientations.

![Home with the media bar](img/desktop/v12-home.jpg)

## Install

In the Jellyfin dashboard, open **Branding** and paste this into **Custom CSS code**:

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/zombie_revived.css);
```

Then add any of the optional imports below on the lines after it.

## Colour schemes

Add one below the main import. Each row of boxes shows the accent first, then the dark shades the scheme uses.

**Default (no scheme)**
![Accent](https://readme-swatches.vercel.app/FFFFFF) ![Accent off](https://readme-swatches.vercel.app/242424) ![Dark](https://readme-swatches.vercel.app/181818) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/303030) ![Apparent](https://readme-swatches.vercel.app/2B2B2B)

**Netflix**
![Accent](https://readme-swatches.vercel.app/E50914) ![Accent off](https://readme-swatches.vercel.app/2A0407) ![Dark](https://readme-swatches.vercel.app/141414) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/2F2F2F) ![Apparent](https://readme-swatches.vercel.app/1C1C1C)

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/color-schemes/netflix.css);
```

**Amazon Prime**
![Accent](https://readme-swatches.vercel.app/00A8E1) ![Accent off](https://readme-swatches.vercel.app/03202B) ![Dark](https://readme-swatches.vercel.app/0F171E) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/1F2D3A) ![Apparent](https://readme-swatches.vercel.app/141F29)

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/color-schemes/amazon-prime.css);
```

**Apple TV**
![Accent](https://readme-swatches.vercel.app/FFFFFF) ![Accent off](https://readme-swatches.vercel.app/242424) ![Dark](https://readme-swatches.vercel.app/141414) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/2C2C2E) ![Apparent](https://readme-swatches.vercel.app/1C1C1E)

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/color-schemes/apple-tv.css);
```

**Disney**
![Accent](https://readme-swatches.vercel.app/0063E5) ![Accent off](https://readme-swatches.vercel.app/04162E) ![Dark](https://readme-swatches.vercel.app/12141C) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/232839) ![Apparent](https://readme-swatches.vercel.app/181B26)

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/color-schemes/disney.css);
```

**HBO Max**
![Accent](https://readme-swatches.vercel.app/991EEB) ![Accent off](https://readme-swatches.vercel.app/1E0733) ![Dark](https://readme-swatches.vercel.app/16121C) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/2B2338) ![Apparent](https://readme-swatches.vercel.app/1D1826)

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/color-schemes/hbo-max.css);
```

**Hulu**
![Accent](https://readme-swatches.vercel.app/1CE783) ![Accent off](https://readme-swatches.vercel.app/052617) ![Dark](https://readme-swatches.vercel.app/101413) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/222A26) ![Apparent](https://readme-swatches.vercel.app/161B19)

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/color-schemes/hulu.css);
```

**YouTube**
![Accent](https://readme-swatches.vercel.app/FF0000) ![Accent off](https://readme-swatches.vercel.app/2B0000) ![Dark](https://readme-swatches.vercel.app/0F0F0F) ![Darkest](https://readme-swatches.vercel.app/000000) ![Highlight](https://readme-swatches.vercel.app/272727) ![Apparent](https://readme-swatches.vercel.app/181818)

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/color-schemes/youtube.css);
```

<details>
<summary>Colour palettes from earlier versions (8)</summary>

These swap the black base for a tinted dark one. Palettes from [ZestyTheme](https://github.com/stpnwf/ZestyTheme/tree/main) also work. Add one below the main import.

**Palette 1**
![Powder Blue](https://readme-swatches.vercel.app/ADDFF4) ![Slate Gray](https://readme-swatches.vercel.app/708090) ![Charcoal](https://readme-swatches.vercel.app/2F363B) ![Jet](https://readme-swatches.vercel.app/1C2124) ![Gunmetal](https://readme-swatches.vercel.app/3C464B) ![Dark Slate](https://readme-swatches.vercel.app/1D2629)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-1.css');
```

**Palette 2**
![Light Steel Blue](https://readme-swatches.vercel.app/A2CDEE) ![Dark Slate Gray](https://readme-swatches.vercel.app/5A686E) ![Onyx](https://readme-swatches.vercel.app/24292E) ![Eerie Black](https://readme-swatches.vercel.app/12171B) ![Outer Space](https://readme-swatches.vercel.app/333C42) ![Midnight](https://readme-swatches.vercel.app/1B2328)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-2.css');
```

**Palette 3**
![Sky Blue](https://readme-swatches.vercel.app/92C7E6) ![Slate Blue](https://readme-swatches.vercel.app/505C63) ![Space Gray](https://readme-swatches.vercel.app/282F34) ![Black Charcoal](https://readme-swatches.vercel.app/161B1F) ![Steel Gray](https://readme-swatches.vercel.app/384248) ![Graphite](https://readme-swatches.vercel.app/192227)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-3.css');
```

**Palette 4**
![Teal](https://readme-swatches.vercel.app/80CBC4) ![Storm Gray](https://readme-swatches.vercel.app/647C83) ![Gunmetal Gray](https://readme-swatches.vercel.app/2D3436) ![Jet Black](https://readme-swatches.vercel.app/191D1F) ![Dark Slate](https://readme-swatches.vercel.app/3C4749) ![Charcoal Gray](https://readme-swatches.vercel.app/162221)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-4.css');
```

**Palette 5**
![Aqua Blue](https://readme-swatches.vercel.app/78BED5) ![Smoky Gray](https://readme-swatches.vercel.app/5A696E) ![Carbon Gray](https://readme-swatches.vercel.app/262E32) ![Ebon](https://readme-swatches.vercel.app/151A1D) ![Granite](https://readme-swatches.vercel.app/364045) ![Iron Gray](https://readme-swatches.vercel.app/142024)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-5.css');
```

**Palette 6**
![Periwinkle](https://readme-swatches.vercel.app/A3B1E0) ![Dusk Gray](https://readme-swatches.vercel.app/626C7C) ![Slate Indigo](https://readme-swatches.vercel.app/2A2D38) ![Deep Indigo](https://readme-swatches.vercel.app/171920) ![Muted Indigo](https://readme-swatches.vercel.app/3A3E4C) ![Night Indigo](https://readme-swatches.vercel.app/1A1C25)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-6.css');
```

**Palette 7**
![Pale Blue](https://readme-swatches.vercel.app/6EB4C8) ![Cadet Gray](https://readme-swatches.vercel.app/4E5D64) ![Storm Cloud](https://readme-swatches.vercel.app/232B2F) ![Raven Black](https://readme-swatches.vercel.app/121719) ![Charcoal Blue](https://readme-swatches.vercel.app/323C41) ![Lead Gray](https://readme-swatches.vercel.app/131E22)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-7.css');
```

**Palette 8**
![Color1](https://readme-swatches.vercel.app/AAAAAA) ![Color2](https://readme-swatches.vercel.app/828282) ![Color3](https://readme-swatches.vercel.app/555555) ![Color4](https://readme-swatches.vercel.app/323232) ![Color5](https://readme-swatches.vercel.app/414141) ![Color6](https://readme-swatches.vercel.app/2D2D2D)

```css
@import url('https://cdn.jsdelivr.net/gh/MakD/zombie-release@main/colorPalette/palette-8.css');
```

</details>

## Media bar (optional)

Zombie works on its own. If you also want the featured hero at the top of the home page, install [Jellyfin Media Bar](https://github.com/MakD/Jellyfin-Media-Bar) and add Zombie's styling for it.

<details>
<summary>Install steps and screenshots</summary>

### 1. Install the Media Bar

Take a backup of `index.html` first.

1. Go to your `jellyfin-web` folder and open `index.html` in a code editor (with administrator rights).
2. Search for `</head>`.
3. Paste this just before `</head>`:

```html
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Archivo+Narrow:ital,wght@0,400..700;1,400..700&family=IBM+Plex+Mono:wght@400;600&display=swap"
    />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/MakD/Jellyfin-Media-Bar@6/slideshowpure.css" />
    <script defer src="https://cdn.jsdelivr.net/gh/MakD/Jellyfin-Media-Bar@6/slideshowpure.js"></script>
```

4. Save, then hard refresh the page (Ctrl+Shift+R) twice.

Custom lists, filters, settings and uninstalling are covered in the [Media Bar README](https://github.com/MakD/Jellyfin-Media-Bar#readme).

### 2. Add Zombie's styling

In **Branding > Custom CSS code**, add this below the main Zombie import:

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/mediabar/zombie-mediabar.css);
```

Zombie styles the bar's default **Marquee** layout, so leave Layout on Marquee in the bar's gear menu.

On phones held upright the hero shows the poster. To show the backdrop instead, which takes less height, add this line below the one above:

```css
@import url(https://cdn.jsdelivr.net/gh/MakD/zombie-release@latest/mediabar/zombie-mediabar-backdrop.css);
```

### How it looks

| Desktop | Tablet (landscape) |
|---|---|
| ![Media bar on desktop](img/desktop/v12-home.jpg) | ![Media bar on a tablet](img/tablet/v12-landscape-home.jpg) |

| Phone (portrait) | Tablet (portrait) | Phone (landscape) |
|---|---|---|
| ![Media bar on a phone](img/mobile/v12-portrait-home.jpg) | ![Media bar on a tablet held upright](img/tablet/v12-portrait-home.jpg) | ![Media bar on a phone held sideways](img/mobile/v12-landscape-home.jpg) |

</details>

## Login background

If the splash screen is enabled in Jellyfin (Dashboard, General), the login page uses it as its background. If it is off, the theme shows its own image. To use your own image in that case, add this to your custom CSS:

```css
:root {
  --zombieLoginImage: url(https://example.com/your-image.jpg);
}
```

## Screenshots

Taken on Jellyfin 12 with the Netflix scheme. More screens for every device are in [`img/desktop`](img/desktop), [`img/mobile`](img/mobile) and [`img/tablet`](img/tablet) (files starting with `v12-`).

### Desktop

| | |
|---|---|
| ![Home with the media bar](img/desktop/v12-home.jpg) | ![Home rows](img/desktop/v12-home-rows.jpg) |
| ![Movie](img/desktop/v12-movie.jpg) | ![Series](img/desktop/v12-series.jpg) |
| ![Library](img/desktop/v12-library.jpg) | ![Person](img/desktop/v12-person.jpg) |
| ![Music home](img/desktop/v12-music-home.jpg) | ![Album](img/desktop/v12-album.jpg) |
| ![Artist](img/desktop/v12-artist.jpg) | ![Now Playing](img/desktop/v12-now-playing.jpg) |
| ![Live TV programs](img/desktop/v12-livetv-programs.jpg) | ![Live TV guide](img/desktop/v12-livetv-guide.jpg) |
| ![Login](img/desktop/v12-login.jpg) | ![Live TV channels](img/desktop/v12-livetv-channels.jpg) |

### Phone (portrait)

| | | | |
|---|---|---|---|
| ![Home](img/mobile/v12-portrait-home.jpg) | ![Home rows](img/mobile/v12-portrait-home-rows.jpg) | ![Movie](img/mobile/v12-portrait-movie.jpg) | ![Series](img/mobile/v12-portrait-series.jpg) |
| ![Person](img/mobile/v12-portrait-person.jpg) | ![Album](img/mobile/v12-portrait-album.jpg) | ![Now Playing](img/mobile/v12-portrait-now-playing.jpg) | ![Live TV](img/mobile/v12-portrait-livetv-programs.jpg) |

### Phone (landscape)

| | |
|---|---|
| ![Home](img/mobile/v12-landscape-home.jpg) | ![Home rows](img/mobile/v12-landscape-home-rows.jpg) |
| ![Movie](img/mobile/v12-landscape-movie.jpg) | ![Series](img/mobile/v12-landscape-series.jpg) |
| ![Album](img/mobile/v12-landscape-album.jpg) | ![Live TV](img/mobile/v12-landscape-livetv-programs.jpg) |

### Tablet (portrait)

| | | |
|---|---|---|
| ![Home](img/tablet/v12-portrait-home.jpg) | ![Movie](img/tablet/v12-portrait-movie.jpg) | ![Album](img/tablet/v12-portrait-album.jpg) |
| ![Home rows](img/tablet/v12-portrait-home-rows.jpg) | ![Live TV guide](img/tablet/v12-portrait-livetv-guide.jpg) | ![Channels](img/tablet/v12-portrait-livetv-channels.jpg) |

### Tablet (landscape)

| | |
|---|---|
| ![Home](img/tablet/v12-landscape-home.jpg) | ![Home rows](img/tablet/v12-landscape-home-rows.jpg) |
| ![Movie](img/tablet/v12-landscape-movie.jpg) | ![Artist](img/tablet/v12-landscape-artist.jpg) |

## Older Jellyfin versions

The theme for Jellyfin 10.9 and its add-ons are no longer maintained. The files are kept in [`graveyard`](graveyard).

## Credits

Huge thanks to the theme creators whose work this builds on: [Zesty](https://github.com/stpnwf/ZestyTheme/tree/main), [JellySkin](https://github.com/prayag17/JellySkin/tree/master), [Ultrachromic](https://github.com/CTalvio/Ultrachromic) and [Jellyfin Landscape](https://github.com/krlsantcard/Jellyfin-10.9/tree/main). Please let me know if I have missed anybody.
