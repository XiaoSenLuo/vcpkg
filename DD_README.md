# 变更
1. 添加 `arm-amd-linux`, `arm-amd-linux-dynamic` triplet, 用于 ZYNQ Linux 应用开发

# 使用

安装软件包时, 指定triplet为 `arm-amd-linux` 或者 `arm-amd-linux-dynamic`

经典模式(class mode):
```bash
vcpkg install fmt:arm-amd-linux
```
或者
```bash
vcpkg install fmt:arm-amd-linux-dynamic
```

清单模式(manifest mode):
- cmake 集成: 添加参数 `-DCMAKE_TOOLCHAIN_FILE:FILEPATH=<VCPKG_ROOT>/scripts/buildsystems/vcpkg.cmake -DVCPKG_MANIFEST_MODE:BOOL=ON -DVCPKG_TARGET_TRIPLET:STRING=arm-amd-linux` 或者 `-DCMAKE_TOOLCHAIN_FILE:FILEPATH=<VCPKG_ROOT>/scripts/buildsystems/vcpkg.cmake -DVCPKG_MANIFEST_MODE:BOOL=ON -DVCPKG_TARGET_TRIPLET:STRING=arm-amd-linux-dynamic`


# 创建自定义triplet




# 创建自定义软件包




