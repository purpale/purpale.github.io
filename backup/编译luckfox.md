> rtl8821cu

```bash
cd /home/pico/rtl8821CU
make clean

make ARCH=arm \
     CROSS_COMPILE=/home/luckfox-pico/tools/linux/toolchain/arm-rockchip830-linux-uclibcgnueabihf/bin/arm-rockchip830-linux-uclibcgnueabihf- \
     KSRC=/home/luckfox-pico/sysdrv/source/objs_kernel \
     USER_EXTRA_CFLAGS="-Wno-error"
```

> 反射屏
```bash

```