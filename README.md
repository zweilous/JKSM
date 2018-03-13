# jksm (jk's save manager) - rosalina-compatible only

#### notes

only the `.3dsx` is able to be used. this fork is only compatible with the homebrew launcher using rosalina as the entrypoint. for old *hax entrypoints, please visit the [original fork by J-D-K](https://github.com/J-D-K/JKSM).

this fork moves the contents of `/jksv` to `/3ds/jksm`. saves must be moved to this new path before being able to access them.

`filter.txt` manually filters out titles from appearing in the titles list after refreshing it.

#### building

build `jksm.3dsx` using `make` with the following installed:

* [naxann's portlibs](https://github.com/Naxann/3ds_portlibs)
	* zlib
	* libpng (requires zlib)
	* freetype (requires libpng)
	* bzip2
* [ctrulib](https://github.com/smealum/ctrulib)
* [citro3d](https://github.com/fincs/citro3d)
* [sf2dlib](https://github.com/xerpi/sf2dlib)
* [sftdlib](https://github.com/xerpi/sftdlib)
* [sfillib](https://github.com/xerpi/sfillib)
