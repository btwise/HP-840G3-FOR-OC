# HP-840G3-FOR-OC
## 细节

- CPU : Intel® Core™ i7-6700U Processor
- 显卡 : Intel HD 520
- 声卡 : Conexant CX20724
- 内存 : DDR4 8G 2133MHZ
- M.2 NVME SSD : THOSHIBA256GB




## Bios/MACOS Version

- Bios : 使用最新
- OC Bootloader : OpenCore 0.5.6（GUI) by N-D-K
- macOS : 10.14.6


## Bios设置

- 关闭安全启动和传统启动，开启UEFI
- 其他默认


## DSDT Patch

- [sys] 加载X86补丁
- [sys] SBUS补丁
- [sys] SSDT-GPRW睡眠补丁
- [sys] SSDT-0d6d补丁
- [bat] SSDT-840BAT电池补丁
- [sys] SSDT-RTC0 CMOS重置补丁
- [sys] SSDT-PNLF-SKL_KBL亮度补丁
- [sys] SSDT-PS2K 键盘补丁
- [sys] SSDT-EC-USBX 仿冒EC补丁

## Drivers64UEFI

- ApfsDriverLoader-64.efi
- FwRuntimeServices.efi
- HFSPlus.efi

## EFI文件
- 内附几个实用efi工具，ScreenshotDxe.efi为截屏工具，BOOT\startup.nsh为获取windows启动路径的shell脚步
