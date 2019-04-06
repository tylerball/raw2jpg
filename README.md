# raw2jpg

Script to convert RAW photos to JPG with Camera Raw/Lightroom adjustments applied.

## install

```sh
brew cask install adobe-dng-converter
brew install exiftool
curl -Lk https://raw.githubusercontent.com/tylerball/raw2jpg/master/raw2jpg > /usr/local/bin/raw2jpg
```

## usage

```
Usage: rawjpg [options] [directories]
    -e, --extensions [FORMATS]       Extensions to search, comma seperated (default 'raf,nef,cr2')
    -v, --[no-]verbose               Run verbosely
    -c, --[no-]cra                   Overwrite jpgs when raw file has Camera Raw adjustments
    -f, --force                      Overwrite existing jpgs
    -h, --help                       Prints this help
```

[goog]:https://support.google.com/photos/answer/6193313?co=GENIE.Platform%3DDesktop&hl=en#raw
