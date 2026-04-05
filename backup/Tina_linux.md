```bash
export ARCH=arm
export CROSS_COMPILE=arm-openwrt-linux-
export PATH=$PATH:/home/purffy/tina-v853-open/prebuilt/rootfsbuilt/arm/toolchain-sunxi-musl-gcc-830/toolchain/bin
export STAGING_DIR=./staging_dir
```

```bash
# 通过串口登录设备，执行以下命令
echo "/etc/init.d/adbd start" >> /etc/init.d/rc.final
chmod +x /etc/init.d/rc.final
```