kernel-tab-3-7.0
================

kernel sources for the galaxy tab 3 7.0

How to compile de kernel & modules
==================================

  $ make all # buils kernel & modules
  $ make kernel # only the kernel
  $ make modules # only modules

IMPORTANT: make sure that KERNEL_TOOLCHAIN_PREFIX points to the right place in
your environment (use absolute paths). If it doesn't, you can overwrite it as follows:

  $ make all KERNEL_TOOLCHAIN_PREFIX=</path/to/toolchain>

  Some notes:
   - toolchain version for arm: arm-eabi-4.6
   - get the toolchain from: git@github.com:cozybit/mesh-injected-phones.git
