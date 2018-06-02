0. `cd` to the directory where you found this file.
1. Ensure your PATH contains the aarch64-linux-android-4.9/bin toolchain 
2. Run `export CROSS_COMPILE=aarch64-linux-android-`
3. Run `export ARCH=arm64`
4. Run `export KBUILD_SRC=$(pwd)`
5. Run `make merge_hi6250_defconfig`
6. Run `make -jX`, where X is the number of logical CPU cores your device has. If the number is too low, or significantly too big, compilation will be slower.
7. Profit!
