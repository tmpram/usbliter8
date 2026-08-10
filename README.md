# usbliter8
usbliter8 builds for extra boards  
**Xiao RP2350**  
**Folder contents:**  
- .uf2 ready to be flashed to the board
* .cmake configuration file for usbliter8 source code build
+ the build commands:
```
cmake -S . -B build -DPICO_BOARD=seeed_xiao_rp2350       -DPICO_SDK_PATH=$PICO_SDK_PATH       -DPICO_TOOLCHAIN_PATH=$PICO_TOOLCHAIN_PATH
cmake --build build
```

