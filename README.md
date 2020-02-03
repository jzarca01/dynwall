# Dynamic Wallpaper Tweak Generator

This script generates dynamic wallpapers for jailbroken iPhones (iOS >= 13) from a few infos and two jpeg images.

## How to use

```shell
./dynwall -n MyAwesomeWallpaper -l Light.jpeg -d another_image.jpeg [-t Thumbnail.png] [-i true]

	-n :: Name of dynamic wallpaper
	-l :: Light filename jpeg
	-d :: Dark filename jpeg
    -t :: Thumbnail filename png
	-i true  :: Install only
```

## Requirements

- A jailbroken iPhone
- Theos
- THEOS set in your .bash_profile
- For install only: THEOS_DEVICE_IP set in your .bash_profile
