<div align="center">

# 🔥 Meteoric Kernel with KernelSU & SUSFS

[![KernelSU](https://img.shields.io/badge/KernelSU-Supported-green)](https://kernelsu.org/)
[![SUSFS](https://img.shields.io/badge/SUSFS-Integrated-orange)](https://gitlab.com/simonpunk/susfs4ksu)
[![Meteoric](https://img.shields.io/badge/Meteoric-Kernel-purple)](https://github.com/MiguVT/kernel_nothing_sm8475_github_actions/tree/clean)

> Note that this code is not made by me, I only adapted it for the Meteoric Kernel, all credits go to the [original authors](https://github.com/WildKernels/GKI_KernelSU_SUSFS), also the code is originally a little messy and not well-documented, I tried to clean it up and rewrite some parts, also removed unnecessary code and improved overall structure, but a messy codebase is still a messy codebase (I rewrited some parts but still messy), Pull Requests are more than welcome!
> The Meteoric Kernel was cleaned by me (Original had hardcoded KSU and SUSFS integration)

</div>

## ⚠️ Your warranty is no longer valid!

I am **not responsible** for bricked devices, damaged hardware, or any issues that arise from using this kernel.

**Please** do thorough research and fully understand the features included in this kernel before flashing it!

By flashing this kernel, **YOU** are choosing to make these modifications. If something goes wrong, **do not blame me**!

---

### 🚨 Proceed at your own risk!

---

## 🔧 About This Project

This project is a **specialized fork** of [WildKernels/GKI_KernelSU_SUSFS](https://github.com/WildKernels/GKI_KernelSU_SUSFS), completely adapted and optimized to build the **Meteoric Kernel** with KernelSU and SUSFS integration.

Unlike the original project that builds generic GKI kernels for multiple Android versions, this fork is **exclusively designed** for the **Meteoric Kernel** - a high-performance custom kernel specifically tailored for Nothing Phone devices.

### 🎯 Key Differences from Original GKI Project:

- **🌟 Meteoric-Specific**: Builds only Meteoric Kernel instead of generic GKI
- **📱 Device-Targeted**: Optimized exclusively for Nothing Phone (sm8475 chipset)
- **🎯 Android 12 Focus**: Specialized for Android 12 (5.10 kernel version) only
- **🔧 Custom Source**: Uses [kernel_nothing_sm8475_github_actions](https://github.com/MiguVT/kernel_nothing_sm8475_github_actions) (clean branch)
- **⚡ Performance Enhanced**: Includes Meteoric's specific optimizations and features

**Meteoric Kernel** delivers exceptional performance and stability for Nothing Phone devices, providing advanced features while maintaining compatibility with the latest KernelSU and SUSFS technologies.

| Component              | Repository                                                                                             | Status        |
| ---------------------- | ------------------------------------------------------------------------------------------------------ | ------------- |
| 🌟 **Meteoric Kernel** | [kernel_nothing_sm8475_github_actions](https://github.com/MiguVT/kernel_nothing_sm8475_github_actions) | ✅ Active     |
| 🔐 **Wild KSU**        | [Wild_KSU](https://github.com/WildKernels/Wild_KSU)                                                    | ✅ Integrated |
| 🛡️ **SUSFS**           | [susfs4ksu](https://gitlab.com/simonpunk/susfs4ksu)                                                    | ✅ Integrated |

---

## 🎯 Supported Devices & Compatibility

### ✅ Supported Devices:

- **Nothing Phone (2)** - sm8475 (Snapdragon 8+ Gen 1) chipset
- **Android 12 based ROMs** (AOSP/LineageOS/Nothing OS)
- **Kernel version**: 5.10 (specifically optimized)

### ⚠️ Important Compatibility Notes:

- **This kernel is NOT compatible with other Android versions** (A13+) - That means no Android 13 kernel, but you can use it on higher Android versions.
- **This kernel is NOT compatible with other devices** (non-sm8475)
- **This kernel is specifically built for Nothing Phone architecture**

### 🔍 Before Installation:

- Verify your device is Nothing Phone (2) with sm8475 chipset
- Ensure you're running Android 12 based ROM
- Check your current kernel version compatibility

---

## 🆚 Meteoric vs Generic GKI Kernels

### 🌟 **Meteoric Kernel Advantages:**

- **Device-Specific Optimizations**: Tailored for Nothing Phone hardware
- **Enhanced Performance**: Custom tweaks for sm8475 chipset
- **Nothing-Specific Features**: Hardware-specific optimizations
- **Stable & Tested**: Thoroughly tested on Nothing devices

### ⚖️ **Why Not Generic GKI:**

- **Generic Nature**: GKI kernels are one-size-fits-all
- **Limited Optimization**: No device-specific enhancements
- **Compatibility Issues**: May not fully utilize Nothing Phone features
- **Performance Gap**: Less optimized for sm8475 architecture

### 💡 **Best Choice for Nothing Phone Users:**

If you own a Nothing Phone (2), the **Meteoric Kernel** is specifically designed for your device and will provide better performance, stability, and feature compatibility compared to generic GKI kernels.

---

## 🔗 Additional Resources

- 🩹 [Kernel Patches](https://github.com/WildKernels/kernel_patches)
- 📜 [Original GKI Build Scripts](https://github.com/WildKernels/GKI_KernelSU_SUSFS)
- ⚡ [Kernel Flasher](https://github.com/fatalcoder524/KernelFlasher)

---

## 📋 Installation Instructions

1. Download the appropriate kernel build for your device
2. Boot into custom recovery (TWRP/OrangeFox)
3. Flash the kernel zip file
4. Reboot and enjoy!

For KernelSU setup, please follow the official guide:

📖 **[KernelSU Installation Guide](https://kernelsu.org/guide/installation.html)**

---

## ✨ Features

### 🔐 **Root & Security Features:**

- **Wild KernelSU**: Enhanced root solution with multi-manager support
- **SUSFS v1.5.12**: Advanced root hiding capabilities
- **Scope-Minimized Manual hooks v1.4**: Improved compatibility
- **Magic Mount Support**: Advanced mounting capabilities
- **Simple & Futile Maphide**: Detection bypassing

### 🌟 **Meteoric-Specific Optimizations:**

- **Nothing Phone Optimizations**: Performance enhancements for sm8475 devices
- **Hardware-Specific Tweaks**: Tailored for Nothing Phone (2) architecture
- **Thermal Management**: Optimized thermal profiles for Nothing devices
- **Power Efficiency**: Battery optimization for sm8475 chipset

### 🚀 **Performance & Networking:**

- **BBR v1**: TCP congestion control optimization
- **IPSet & Wireguard Support**: Advanced networking capabilities
- **Ptrace Patch Support**: Compatibility for older systems
- **LTO Optimizations**: Link-time optimizations for better performance

---

## 🏆 Credits

- 🌟 **Meteoric Kernel**: Developed by [HELLBOY017](https://github.com/HELLBOY017/kernel_nothing_sm8475/) and maintained by [MiguVT](https://github.com/MiguVT/kernel_nothing_sm8475_github_actions/tree/clean)
- 🔐 **WildKernels**: Based on a lot of work by [WildKernels](https://github.com/WildKernels/)
- 🚀 **KernelSU**: Originally by [tiann](https://github.com/tiann/KernelSU)
- 🛡️ **SUSFS**: Developed by [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git)
- 📦 **SUSFS Module**: Developed by [sidex15](https://github.com/sidex15)
- 🏗️ **Build System**: Adapted from [WildKernels/GKI_KernelSU_SUSFS](https://github.com/WildKernels/GKI_KernelSU_SUSFS)

🙏 Special thanks to the open-source community and Nothing Phone developers!

---

## 💬 Support

If you encounter any issues or need help, feel free to:

- 🐛 Open an issue in this repository
- 💬 Check the original Meteoric Kernel repository
- 📱 Join our Telegram group

---

## ⚠️ Disclaimer

Flashing this kernel will void your warranty, and there is always a risk of bricking your device. Please make sure to:

- 💾 Back up your data and current kernel
- 🧠 Understand the risks before proceeding
- 📱 Ensure compatibility with your Nothing Phone model

**🚨 Proceed at your own risk!**

---

<div align="center">

## 📱 Connect With Us

[![Telegram](https://img.shields.io/badge/Telegram-TheWildJames-blue?logo=telegram)](https://t.me/TheWildJames)
[![Telegram Group](https://img.shields.io/badge/Telegram-Wild__Kernels-blue?logo=telegram)](https://t.me/WildKernels)

</div>

---

## 🌟 Special Thanks

**These amazing people help make this project possible! ❤️**

| Contributor                                                | Contribution                                   |
| ---------------------------------------------------------- | ---------------------------------------------- |
| 🛡️ [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) | Created SUSFS!                                 |
| 📦 [sidex15](https://github.com/sidex15)                   | Created module!                                |
| 🌟 [MiguVT](https://github.com/MiguVT)                     | Implementation for supporting Meteoric Kernel! |
| 🏗️ [WildKernels](https://github.com/WildKernels)           | Build system foundation!                       |
| 🩹 [backslashxx](https://github.com/backslashxx)           | Helped with patches!                           |
| 🔧 [Teemo](https://github.com/liqideqq)                    | Helped with patches!                           |
| 💝 [幕落](https://github.com/MuLuo688)                     | Donation!                                      |

_If you have contributed and are not listed here, please remind me!_ 🙏
