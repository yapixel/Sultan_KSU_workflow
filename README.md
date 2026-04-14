# Sultan Matrix — Unified Pixel Kernel

A high-performance, security-focused kernel for Pixel devices (Zuma/Zpro), merging the stability of **Sultan Kernel** with advanced stealth and networking features.

## 🚀 Key Features
- **Stealth Core:** Integrated **SUSFS** support and **KernelSU** (xxKSU/KowSU variants).
- **Fortress Networking:** Full support for `atp4pixel` suite including BBR v1, IPSet (64k), and XFRM sub-policies.
- **Optimized Build:** Compiled with **GCC 14.2.0** for maximum stability and reproducibility.
- **Hookless Security:** Option for hookless xxKSU via LSM security hooks (No KProbes).

---

## 📦 Build Variants

| Variant | Description | Base Source |
| :--- | :--- | :--- |
| **xxKSU-SUSFS** | Pre-integrated SUSFS + xxKSU for maximum stealth. | [Trijal08 Anaconda](https://github.com/Trijal08/anaconda_kernel_google_tensynos) |
| **KowSU-SUSFS** | Official Sultan base with manual KowSU/SUSFS bridging. | [Official Sultan](https://github.com/kerneltoast/android_kernel_google_tensynos) |
| **xxKSU** | Hookless KSU without SUSFS. Clean and efficient. | [Official Sultan](https://github.com/kerneltoast/android_kernel_google_tensynos) |

---

## 🤝 Credits & Acknowledgments

This project is made possible thanks to the work of the following developers:

### 🛠️ Kernel & Core Logic
* **[Sultan (kerneltoast)](https://github.com/kerneltoast)** - For the exceptional Sultan Kernel base.
* **[Trijal08](https://github.com/Trijal08)** - For the **Anaconda Kernel** fork and pre-patched **KernelSU** source.
* **[Yapixel](https://github.com/yapixel)** - For kernel patches and specialized configuration logic.

### 🛡️ Stealth & Security
* **[KernelSU Team](https://github.com/tiann/KernelSU)** - For the revolutionary root solution.
* **[simonpunk](https://gitlab.com/simonpunk/susfs4ksu)** - The creator of **SUSFS**.
* **[KOWX712](https://github.com/KOWX712)** & **[backslashxx](https://github.com/backslashxx)** - For specialized KernelSU integration methods.

### 🔧 Tools & Distribution
* **[TheWildJames](https://github.com/TheWildJames)** - AnyKernel3 distribution template.
* **[TheSillyOk](https://github.com/TheSillyOk)** - Build automation scripts.
