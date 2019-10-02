## setup

How to setup the VIM3 from scratch

---

VIM3 Ubuntu images are found [here](https://docs.khadas.com/vim3/FirmwareUbuntu.html).

1. Download the newest EMMC Server image (currently [VIM3\_Ubuntu-server-bionic\_Linux-4.9\_arm64\_EMMC\_V20190830](https://dl.khadas.com/Firmware/VIM3/Ubuntu/EMMC/VIM3_Ubuntu-server-bionic_Linux-4.9_arm64_EMMC_V20190830.7z)).
2. Boot into Upgrade Mode ([Use TST Mode](https://docs.khadas.com/vim3/HowtoBootIntoUpgradeMode.html))
3. Follow the Ubuntu instructions [here](https://docs.khadas.com/vim3/UpgradeViaUSBCable.html)

Plug the VIM3 into a router and find its IP (use `nmap` or check DHCP table on router).

* `ssh root@[vim3\_ip\_address]`, password:khadas

If all goes well, we shouldn't have to do this again...
