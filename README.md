# Genshin Fonts

**Alphabets in Teyvat!**

[中文](README_CN.md) | English

![Font sample](readme_assets/Examples.svg)

## Usage

### Get Fonts

You can get built fonts under `Build` folder.

*Note: On Windows, TTF version is recommended.*

### About Inazuma Language (No Vert)

![Inazuma_Vert](readme_assets/Inazuma_Vert.png)

Inazuma Languange has two versions, one with Opentype feature `vert`, the other without. With this feature and supported APPs (e.g. [LibreOffice](https://www.libreoffice.org/)), Inazuma Language can be written vertically, as it in game. However, when using Adobe APPs, please select the version without `vert`.

## Building

0. Install [AFDKO](https://github.com/adobe-type-tools/afdko).

1. Clone this repo:

        $ git clone https://github.com/Wenti-D/GenshinFonts
        $ cd GenshinFonts

2. Build OTF:

        $ makeotf -f <UFO folder>

    e.g.:

        $ makeotf -f TeyvatCommonLanguage.ufo

3. Transform OTF to TTF (optional):

        $ otf2ttf input <OTF file>

    e.g.:

        $ otf2ttf input TeyvatCommonLanguage-Regular.otf

## Contributing

If have any problems, especially design problems (glyph, size, kerning, etc.), please open an issue.