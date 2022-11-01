# Genshin_Fonts

**Alphabets in Teyvat!**

![Font sample](readme_assets/Examples.png)

From top to bottom: 
 - [Source Han Serif](https://github.com/adobe-fonts/source-han-serif)
 - [Latin Modern Roman](https://www.ctan.org/tex-archive/fonts/lm/fonts/opentype/public/lm)
 - Teyvat Common Language
 - Khaenri'ah Language

## Get Fonts

You can get built fonts under `Build` folder.

*Note: On Windows, TTF version is recommended.*

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