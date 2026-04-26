```markdown
# 💻 Operating Systems Lab (xv6)

Welcome to my Operating Systems repository! This repository contains the implementation of various assignments and labs based on the **xv6** operating system. xv6 is a modern re-implementation of the Sixth Edition Unix (V6) developed by MIT for educational purposes.

Through these labs, I have explored the inner workings of operating systems, including process management, memory allocation, system calls, concurrency, and file systems.

---

## 🛠️ Tech Stack & Tools

* **Languages:** C, x86 Assembly
* **Environment:** Linux (Ubuntu)
* **Emulator:** QEMU
* **Build System:** Makefile
* **Debugging:** GDB

---

## 📂 Labs Overview

This repository is structured into several labs, each focusing on a specific subsystem of the operating system:

### [Lab 1: Booting and PC Utilities](./lab1)
* Introduction to the xv6 environment.
* Familiarization with x86 assembly and the boot process.
* Implementation of basic UNIX utilities (e.g., `sleep`, `pingpong`, `primes`, `find`, `xargs`).

### [Lab 2: System Calls](./lab2)
* Deep dive into the kernel-space and user-space boundary.
* Implementation of custom system calls (e.g., `trace` to monitor system calls, and `sysinfo` to collect system data).

### [Lab 3: Page Tables and Memory Management](./lab3)
* Understanding the xv6 virtual memory subsystem.
* Manipulating page tables to optimize memory usage and isolate processes.
* Implementation of features like `Print a page table` and user-level page mappings.

### [Lab 4: Traps and Interrupts](./lab4)
* Handling exceptions, interrupts, and traps in x86.
* Implementing the mechanism to save and restore context during hardware interrupts and software traps.
* Developing the `alarm` system call to periodically interrupt a process.

### [Lab 5: Copy-on-Write (COW) Fork](./lab5)
* Optimization of the `fork()` system call.
* Implementation of the Copy-on-Write mechanism to defer page allocation until a process attempts to modify a shared memory page.

---

## 🚀 How to Run

To build and run the xv6 operating system locally, you need a Linux environment with the RISC-V or x86 toolchain and QEMU installed.

### 1. Install Dependencies (Ubuntu/Debian)
```bash
sudo apt-get update
sudo apt-get install git build-essential gdb-multiarch qemu-system-misc gcc-riscv64-linux-gnu binutils-riscv64-linux-gnu 
```

### 2. Clone the Repository
```bash
git clone [https://github.com/sajadTaghizade/-OS.git](https://github.com/sajadTaghizade/-OS.git)
cd -OS
```

### 3. Compile and Run
To start the emulator and boot the xv6 kernel:
```bash
make qemu
```
To exit QEMU, press `Ctrl-A` then `X`.

---

## 👨‍💻 Author

**Sajjad Taghizadeh**
* Computer Engineering Student @ University of Tehran
* [GitHub Profile](https://github.com/sajadTaghizade)
* [LinkedIn](https://www.linkedin.com/in/sajjad-taghizadeh)

```
