# cmake-toolchain
常用cmake-toolchain-file

## aarch64-linux-toolchain.cmake

  aarch64-linux平台使用  gcc-linaro-aarch64-linux-gnu工具链,
  需要将aarch64-linux-gnu-gcc的路径加入环境变量

## arm-linux-toolchain.cmake

  arm-linux平台使用  gcc-linaro-arm-linux-gnu工具链,
  需要将arm-linux-gnu-gcc的路径加入环境变量

## arm-android-toolchain.cmake

  居于NDK的编译文件,需要讲NDK的路径设置到环境变量NDK
    
## arm-qnx-toolchain.cmake
   qnx-arm-sdp600 将arm-unknown-nto-qnx6.6.0eabi-gcc路径加入环境变量
