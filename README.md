# Sunset for OpenWallpaper

Sunset is simple video wallpaper for the [OpenWallpaper Plasma][wallpaper_plasma].
Video demonstration: [YouTube][youtube_sunset] | [Reddit][reddit_link]

Author: [Link][author].

[Download][video_link] video and add to `Sunset`folder.

![preview][preview_img]

## Parametres

All of the wallpaper packages must have `wallpaper.ini` file with the information below:


### Information about package and author
|  Variable    | Type           | Description               | Wallpaper Type  |  Necessary  |
|    :---:     |     :---:      |     :---:                 |     :---:       |    :---:    |
| Name         | String         | Name of current package   | ALL             | +           |
| Version      | String         | Package version           | ALL             | -           |
| Author       | String         | Author name               | ALL             | -           |
| Email        | String         | Author email              | ALL             | -           |
| AuthorLink   | String         | Author website            | ALL             | -           |
| Comment      | String         | Small text about package  | ALL             | -           |

### Settings parameters
|  Variable    | Type           | Description               | Wallpaper Type  |  Necessary  |
|    :---:     |     :---:      |     :---:                 |     :---:       |    :---:    |
| Type         | String         | One of three types        | ALL             | +           |
| Music        | Bool           | Have music or not         | OGL, Gif        | +-          |
| StartVolume  | Float          | Start volume              | ALL             | +-          |
| FillMode     | String         | Video fill mode           | Video           | -           |

### Resources

|  Variable    | Type           | Description               | Wallpaper Type  |  Necessary  |
|    :---:     |     :---:      |     :---:                 |     :---:       |    :---:    |
| Source       | String         | Path to package source    | ALL             | +           |
| MusicSource  | String         | Path to music source      | ALL             | +-          |
| PreviewImage | String         | Preview image for Manager | ALL             | +           |


About FillMode you can read in [Qt Documentation][qt_fillmode_doc].

## How to create the wallpaper package

* Create `wallpaper.ini` and set needed variables. See Parametres above
* Add source files (videos, gifs or shared libraries(with source))
* Share!

## Links

* [OpenWallpaper Plasma][wallpaper_plasma]
* [OpenWallpaper Manager][wallpaper_manager]

## Author

* [Link][author]


[//]: # (LINKS)
[qt_doc]: https://doc.qt.io/qt-5/reference-overview.html
[qt_fillmode_doc]: https://doc.qt.io/qt-5/qml-qtmultimedia-video.html#fillMode-prop
[youtube_sunset]: https://youtu.be/kRmzwNjYGOI
[author]: http://www.simpsonsworld.com/region-simpsons

[preview_img]: docs/preview_gh.png
[video_link]: https://drive.google.com/open?id=1uAIacXSSIcZG3umQgVYmFmqWRPOcbM8-
[reddit_link]: https://www.reddit.com/r/OpenWallpaper/comments/ex97a9/sunset/
[wallpaper_manager]: https://github.com/Samsuper12/OpenWallpaper-Manager
[wallpaper_plasma]: https://github.com/Samsuper12/OpenWallpaper-Plasma
