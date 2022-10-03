# DarkPapers contributing guide

Thank you for investing your time in contributing to my project! This file will tell you what you need to know to contribute to DarkPapers. Any contribution you make will be appreciated! <3

First of all, read our [Code of Conduct](./CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

## Wallpaper guidelines

Please keep your wallpapers as close as possible to these guidelines:
- 21:9 aspect ratio images, with (preferably) 2160x4800 resolution,
- Minimalistic, flat artstyle,
- Pastel colors,
- PNG extension.

If possible, try to provide Amoled Black/Dark/Light variants of the wallpaper with the Amoled/Dark backgrounds using #000000 and #202020 colors .

## Adding a wallpaper into DarkPapers

1. Put your wallpaper into the ./img folder in the main directory of DarkPapers
2. Locate the frames.json file and in it add your wallpaper entries. For example:
```
   {
      "name":"tequilaOS (Light)",
      "author":"DarkPlayer",
      "url":"https://raw.githubusercontent.com/DarkPlayerr/darkpapers/darkpapers/img/tequilaOS%20(light).png",
      "dimensions":"2160x4800",
      "collections":"doodles,tequilaOS"
   }
```

Make sure to link where your wallpaper will be located on your repository. If you need any guidance, check out this [wiki page.](https://github.com/jahirfiquitiva/Frames/wiki/Add-Wallpapers)

DarkPapers has these collections already (blobs, doodles, landscapes, shapes, tequilaOS), but if you think your wallpaper does not fit into any one of these categories, then feel free to make a new one.
