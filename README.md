## [Replaced by this repository](https://github.com/robertkirkman/sm64ex-bbb-doc)

kmscube
=======
Fork of freedesktop kmscube with the bare minimum stripped out (OpenGL ES 3.0+ 
dependent features) to get it to compile and run on the BeagleBone Black's 
PowerVR SGX530 GPU with version 1.17.4948957 of the proprietary userspace libraries.
**many features untested, use at your own risk**.

---

kmscube is a little demonstration program for how to drive bare metal graphics
without a compositor like X11, wayland or similar, using DRM/KMS (kernel mode
setting), GBM (graphics buffer manager) and EGL for rendering content using
OpenGL or OpenGL ES.

The upstream of kmscube is available at https://gitlab.freedesktop.org/mesa/kmscube/
