# sdl2

SDL 2.30.9: windows, input and 2D drawing for games and programs (X11 backend: start the X server with tos-x first); headers and libraries to build against it

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install sdl2
```

| | |
|---|---|
| Version | 2.30.9-2 |
| Licence | Zlib |
| Upstream | https://libsdl.org |
| Needs | [`xorg`](https://github.com/Artfical/tpkg-xorg) |
| Needs tOS build | 618 or newer |
| Size | 2908674 bytes (10143624 unpacked) |
| SHA-256 of the `.tpkg` | `dc9afeba166fd6b93791122958afc10284a013d323e8eb4654c9101dcd16039d` |

## Commands it adds

| Command | Runs |
|---|---|
| `sdl2-config` | `bin/sdl2-config` |

## Download

The package file (`sdl2-2.30.9-2.tpkg`) and the sources it was built from are the assets of the
[v2.30.9-2 release](https://github.com/Artfical/tpkg-sdl2/releases/tag/v2.30.9-2).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `SDL2-2.30.9.tar.gz`

Check a download: `sha256sum sdl2-2.30.9-2.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: Zlib. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
