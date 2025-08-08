# archCORE Kernel ✨

![GitHub last commit](https://img.shields.io/github/last-commit/c0smic-Lab/kernel_xiaomi_sm6250?style=for-the-badge&logo=github&color=a6e3a1&logoColor=D9E0EE&labelColor=302D41)
![Kernel Version](https://img.shields.io/badge/Kernel-4.14.356-blue.svg?style=for-the-badge&logo=linux&logoColor=D9E0EE)
![Clang Version](https://img.shields.io/badge/Clang-20.1.8-orange.svg?style=for-the-badge&logo=llvm&logoColor=D9E0EE)

Welcome to the official repository for **archCORE Kernel**. This is where I will be posting all the new releases. The kernel is optimized for the best core features to give you a smooth and efficient experience.

---

### ℹ️ About archCORE

**archCORE** is a custom kernel built with performance and stability in mind. The primary goal is to provide the best possible core functionality without unnecessary bloat.

* **Base Kernel:** The kernel is based on the solid foundation of [c0smic-Lab's kernel_xiaomi_sm6250](https://github.com/c0smic-Lab/kernel_xiaomi_sm6250).
* **Optimization Focus:** Tuned for optimal core feature performance.
* **Release Cycle:** New builds will be released occasionally. Stay tuned!

---

### ⚠️ IMPORTANT: Please Read Before Flashing!

**Your warranty is now void. I am not responsible for bricked devices, dead SD cards, or any other hardware/software issues that may arise from flashing this kernel.** Please do some research if you are new to flashing custom kernels.

* 🛑 **BACKUP YOUR DATA:** Before proceeding, make sure you have a complete backup of your important data.
* 💾 **Backup `boot.img` and `dtbo.img`:** It is **CRUCIAL** that you back up your current `boot.img` and `dtbo.img` partitions before flashing `archCORE`.
* **Recovery from Bootloop:** If you encounter a bootloop or your device fails to boot after flashing, please restore the `boot.img` and `dtbo.img` you backed up earlier. This will revert the changes and get your device working again.

---

### 💻 My Humble Build Machine (The Potato PC)

This kernel is proudly compiled on a machine that has stood the test of time! It's a testament to what you can achieve even with modest hardware.

* **CPU:** 🥔 Intel Pentium G2020 @ 2.9GHz (Dual-Core)
* **GPU:** 📺 Integrated Intel HD Graphics
* **RAM:** 🧠 4GB ADATA DDR3 RAM
* **Storage:** 💾 1TB Western Digital HDD
* **Age:** 🕰️ A venerable 12 years old!

---

### ⚙️ Build & Compilation Details

Here are the specifics of the environment used to compile this kernel:

* **Compiler:** `LLVM Clang 20.1.8`
* **Kernel Version:** `4.14.356`
* **Host OS:** `Manjaro Linux` with the `i3` Window Manager
* **Supported OS:** `Android 13` to `Android 16`
* **KernelSU-NEXT:** `Supported` & `Manually Hooked Latest` 

---

### 🐞 Bug Reports & Support

Found a bug? Have a question? Feel free to reach out.

* **Telegram:** For bug reports or support, please send me a direct message on Telegram: **[@sahorkot](https://t.me/sahorkot)**

Please provide as much detail as possible when reporting a bug, including your device variant and the steps to reproduce the issue.

---

### 🙏 Credits & Thanks

A huge thank you to the developers and maintainers of the base kernel source.

* **c0smic-Lab:** For the amazing [kernel_xiaomi_sm6250](https://github.com/c0smic-Lab/kernel_xiaomi_sm6250) source.

Happy Flashing! 🚀
