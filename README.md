
These test images are used to figure out various video problems.

`static` includes static images which are useful (mostly generated from
gstreamer).

 - The `jpg` script evaluates how the test patterns look / work after being jpg
   compressed. This is useful for understanding how the JPEG encoder on the
   HDMI2USB will effect these test images.

`dynamic` includes scripts which generate dynamic output (mostly using
gstreamer).

# Ubuntu

```bash
apt-get install python3-scipy python3-pil
apt-get install apt-get install gstreamer1.0-plugins-* gstreamer-tools
```
