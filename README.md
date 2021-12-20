# Hackintosh-Dell3991
Dell ChengMing 3991 OpenCore 0.7.6 macOS Monterey 12.0.1

# Dell.ChengMing.3991-OpenCore.0.6.4-macOS.Big.Sur.11.1
硬软件信息：

|   条目   |                                        内容                                          |
| -------- | ----------------------------------------------------------------------------------- |
| Model    | Dell ChengMing 3991                                                                 |
| CPU      | OctalCore Intel Core i7-10700, 4700 MHz (47 x 100)                                  |
| iGPU     | Intel(R) UHD Graphics 630                                                           |
| NVGPU    | NVIDIA GeForce GT 730                                                               |
| Audio    | ALC256                                                                              |
| Disk     | KBG40ZNS256G NVMe KIOXIA 256GB                                                      |
| OpenCore | OpenCore 0.7.6 release                                                              |

## BIOS配置
- General → Advanced Boot Options：全部取消勾选
- System Configuration → SATA Operation：勾选AHCI
- Secure Boot → Secure Boot Enable：取消勾选
- Intel® Software Guard Extensions™ → Intel® SGX™ Enable：选择Disabled
- Power Management → Block Sleep：一般不勾选，否则不能进入深度睡眠，深度睡眠影响可切换
- Virtualization Support → VT for Direct I/O：取消勾选

## NVGPU 驱动
[Geforce-Kepler-patcher](https://github.com/chris1111/Geforce-Kepler-patcher)
