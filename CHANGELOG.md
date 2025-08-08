# archCORE Kernel Changelog

---

### **🚀 Release: August 08, 2025**

This is a major update focused on performance, stability, and reducing kernel size.

**✨ Key Changes:**

* **KernelSU & Stability** 🔧
    * Removed `kprobes` due to instability issues.
    * The kernel has been manually patched to support `KernelSU-Next`, providing a more reliable manual hooking mechanism.

* **Driver & Module Cleanup** 🧹
    * Removed several unused HID and input drivers (e.g., for joysticks, PS/2 peripherals, Nintendo controllers) to slim down the kernel.
    * Removed the `WireGuard` driver.
    * Configured kernel module compression and enabled the trimming of unused modules for a smaller footprint.

* **CPU & Performance Optimization** ⚡
    * **`Schedutil` is now the default CPU frequency governor**, offering a great balance of performance and efficiency. Unused governors have been removed.
    * The kernel is now compiled with full **LLVM LTO (Link-Time Optimization)** and **Polly** optimizations for maximum performance.
    * The final build is **stripped** of unnecessary debug symbols and information, making it lean and efficient.

* **Power & Network Management** 🔋
    * Enabled **`autosleep` mode** by default to improve power management when the device is idle.
    * **`BBR` is now the default TCP congestion control algorithm**. Developed by Google, it provides superior network performance.
    * Added `CUBIC`, `BIC`, and `HTCP` as optional kernel modules for users who wish to experiment.

---
