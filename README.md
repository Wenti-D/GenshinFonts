# Genshin_Fonts

**Alphabets in Teyvat!**

![Font sample](readme_assets/Examples.png)

From top to bottom: Source Han Serif, Latin Modern Roman, Khaenri'ah Language and Teyvat Common Language

## Get Fonts

You can get built fonts under "Build" folder.

Note: On Windows, ttf is recommended.

## Building

Take Teyvat Common Language for example. 

You need [AFDKO](https://github.com/adobe-type-tools/afdko) installed first.

Clone this repo:

    $ git clone https://github.com/Wenti-D/Genshin_Fonts

Build otf:

    $ makeotf -f Teyvat_Common_Language.ufo

Transform it to ttf:

    $ otf2ttf input TeyvatCommonLanguage-Regular.otf