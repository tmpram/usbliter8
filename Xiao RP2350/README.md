# usbliter8
(it is not working for Xiao RP2350)
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
**used pins:** GPIO4 and GPIO5
**Wiring**  
![Alt text](Xiao%20RP2350/Xiao%20RP2350_GPIO4_5.jpg/ "This is the hover title")


