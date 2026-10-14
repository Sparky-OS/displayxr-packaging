# DisplayXR packaging for Sparky Stereo OS

Debian packaging of [DisplayXR](https://github.com/DisplayXR/displayxr-runtime), the open OpenXR runtime for 3D displays, for Sparky Stereo OS.

- **Built by Sparky Stereo OS from upstream DisplayXR.** The code lives in the DisplayXR organisation, the project's neutral home; this repository holds only the packaging.
- **From release tags only.** A version ships when DisplayXR says the release is ready.
- **Reviewed by DisplayXR.** Every packaging change comes as a pull request, with the DisplayXR maintainers as reviewers.
- **Bugs:** report them to [Sparky Stereo OS](https://github.com/Sparky-OS/sparky-stereo-os/issues) first; whatever turns out to be upstream goes to DisplayXR.
- **Licence:** the packaging is under the Boost Software License 1.0 (BSL-1.0), the same as DisplayXR, which keeps its licence file by file, with DisplayXR and its authors named in `debian/copyright`.

The KWin side, the window-geometry publisher, ships from the Sparky-OS KWin branch `stereo3d` as `displayxr-window-geometry-publisher-kwin`.

Terms agreed with DisplayXR in [displayxr-runtime#1928](https://github.com/DisplayXR/displayxr-runtime/issues/1928).
