# lewhfree/CoreCrypto

Fork of darlinghq/darling-corecrypto. Compiles to a static library on any Linux distribution.

This fork was created and modified to work with [AltServer-Linux](https://github.com/lewhfree/AltServer-Linux) and any other projects that need the Apple's CoreCrypto library.

## Changes

- Changed `CMakeLists.txt` to remove the option to build for Darling option.
- Fixed code in `src/ccmd4.c` that wasn't compiling.
- Added `make install` functionality.

## Building

```
# git clone https://github.com/lewhfree/corecrypto
# cd corecrypto
# mkdir build
# cd build
# cmake ..
# make
# make install
```

## License

The Darling-CoreCrypto project is licensed under GPLv3 (A copy of the GNU GPLv3 License can be found in the root of this directory or at [https://gnu.org/](https://www.gnu.org/licenses/gpl-3.0.en.html)).

All changes made by lewhfree (which can be found in the Git commit history) are licensed under the Unlicense. See: [https://unlicense.org/](https://unlicense.org/).
