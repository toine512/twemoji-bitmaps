# Bitmap renders of Twemoji

Automated render of [Twemoji](https://github.com/jdecked/twemoji) SVG sources as PNG images, powered by GitHub Actions. \
Twemoji repository is checked for a new release every day at 11:00 UTC.

## Available renders
### Downloads

Each target is zipped as part of the [release](https://github.com/toine512/twemoji-bitmaps/releases). \
You can also pick individual files browsing the `main` branch.

Files can be distributed through jsDelivr. \
Latest: \
`https://cdn.jsdelivr.net/gh/toine512/twemoji-bitmaps@main/<target>/<file>` \
Specific version: \
`https://cdn.jsdelivr.net/gh/toine512/twemoji-bitmaps@<tag>/<target>/<file>` \
Examples: \
`https://cdn.jsdelivr.net/gh/toine512/twemoji-bitmaps@main/128x128_png32/1f382.png` \
`https://cdn.jsdelivr.net/gh/toine512/twemoji-bitmaps@v14.1.2/128x128_png32/1f9d0.png`

### Targets

Folder name structure: `<width>x<height>_<format>`

| \<format\> | Description | Background | Lossy |
| :---: | :--- | :---: | :---: |
| png32 | 8 bit/channel RGBA PNG | trans | N |
| png8 | Indexed PNG with 8 bit/channel adaptive RGB palette + 8 bit adaptive A palette | trans | Y |

### Sources

Twemoji repository used is [jdecked/twemoji](https://github.com/jdecked/twemoji). \
Sources are the `assets/svg` directory taken from latest release tag of the `main` branch.

## Licensing

Twemoji graphics are licensed under [Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/). \
Refer to https://github.com/jdecked/twemoji for more information about authors.
