# `eudev_jll.jl` (v3.2.9+0)

This is an autogenerated package constructed using [`BinaryBuilder.jl`](https://github.com/JuliaPackaging/BinaryBuilder.jl). The originating [`build_tarballs.jl`](https://github.com/JuliaPackaging/Yggdrasil/blob/ffbd3c78ea8f2d322be3aae541d43d849fc4d5ed/E/eudev/build_tarballs.jl) script can be found on [`Yggdrasil`](https://github.com/JuliaPackaging/Yggdrasil/), the community build tree.  If you have any issue, please report it to the Yggdrasil [bug tracker](https://github.com/JuliaPackaging/Yggdrasil/issues).

For more details about JLL packages and how to use them, see `BinaryBuilder.jl` [documentation](https://juliapackaging.github.io/BinaryBuilder.jl/dev/jll/).

## Sources

The tarballs for `eudev_jll.jl` have been built from these sources:

* compressed archive: https://dev.gentoo.org/~blueness/eudev/eudev-3.2.9.tar.gz (SHA256 checksum: `89618619084a19e1451d373c43f141b469c9fd09767973d73dd268b92074d4fc`)

## Platforms

`eudev_jll.jl` is available for the following platforms:

* `Linux aarch64 {libc=glibc}` (`aarch64-linux-gnu`)
* `Linux aarch64 {libc=musl}` (`aarch64-linux-musl`)
* `Linux armv7l {call_abi=eabihf, libc=glibc}` (`armv7l-linux-gnueabihf`)
* `Linux armv7l {call_abi=eabihf, libc=musl}` (`armv7l-linux-musleabihf`)
* `Linux i686 {libc=glibc}` (`i686-linux-gnu`)
* `Linux i686 {libc=musl}` (`i686-linux-musl`)
* `Linux powerpc64le {libc=glibc}` (`powerpc64le-linux-gnu`)
* `Linux x86_64 {libc=glibc}` (`x86_64-linux-gnu`)
* `Linux x86_64 {libc=musl}` (`x86_64-linux-musl`)

## Dependencies

The following JLL packages are required by `eudev_jll.jl`:

* [`gperf_jll`](https://github.com/JuliaBinaryWrappers/gperf_jll.jl)

## Products

The code bindings within this package are autogenerated from the following `Products`:

* `LibraryProduct`: `libudev`
* `ExecutableProduct`: `udevadm`
* `ExecutableProduct`: `udevd`