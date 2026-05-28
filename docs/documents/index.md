Documents
## Document #1: Why is a kernel?
Kernels, sometimes called the "system core," are the bridge between software and hardware. It controls CPU usage, processes, and hardware (input/output, abbreviated I/O, also called stdin/stdout in programming contexts).
For example:
The keyboard sends a key to the device (Input) --> Keyboard driver --> Kernel processes --> Input event --> The kernel places this in the output, located at /dev/stdout (a symbolic link to /proc/self/fd/1).
---
## Document #2: So, kernels are FULL OSes?
A complete operating system is not only the kernel.
The kernel provides interfaces such as /dev, /proc, and /sys, which expose hardware and system information to user space.
User space includes applications, libraries, and binaries typically located in directories like /usr and /opt.
Together, kernel and user space form a complete operating system.
---
## Distributions
Linux distributions are complete operating systems built on top of the Linux kernel.
For beginners, we can recommend...:
### Stable
- Linux Mint
- Debian
- Ubuntu LTS
- LMDE (Linux Mint Debian Edition)
### Gaming and mid-stable
- CachyOS
### For those who have already learned a little
- Fedora Linux
