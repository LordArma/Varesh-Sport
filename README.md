# Varesh Sport
I use these scripts as a reporter in Varesh Sport. :)

## What vsw.sh do?
Crop all JPG or JPEG images to 1080x1080 and then add a PNG watermark on bottom right corner.

First argument: Source DIR.
Second argument: The PNG image's path.
Third argument: Destination DIR.

Example:
```
vsw.sh "YOUR/SOURCE/PATH" "THE/PATH/OF/YOUR/WATERMARK.png" "YOUR/DESTINATION/PATH"
```

## What vswhd.sh do?
It's same as vsw.sh but it crop all images to 1920x1080.

## Important Note
ImageMagick is required to process images.
