Samsung Galaxy A05s (SM-A057F) Kernel Source

Kernel source release for Samsung Galaxy A05s (SM-A057F) based on firmware A057FXXSDDZB3 and Android 15.

Device Information

- Device: Samsung Galaxy A05s
- Model: SM-A057F
- Chipset: Qualcomm Snapdragon 680 (SM6225)
- Android Version: 15
- Firmware: A057FXXSDDZB3
- Architecture: arm64

Source Contents

This repository contains the Samsung Open Source Release package including:

- Kernel Source
- Kernel Platform Sources
- Qualcomm Vendor Sources
- Build Scripts

KVM Support

This source is intended for development and research related to Kernel-based Virtual Machine (KVM) support on the Snapdragon 680 platform.

KVM (Kernel-based Virtual Machine) is a Linux kernel virtualization technology that allows the device to run virtual machines with hardware-assisted virtualization.

Potential use cases include:

- Android Virtualization Framework (AVF)
- pKVM experimentation
- Virtual machine research
- Security isolation testing
- Development of virtualization environments on ARM64

Relevant Kernel Features

Typical KVM-related options include:

CONFIG_KVM=y
CONFIG_KVM_ARM_HOST=y
CONFIG_KVM_ARM_PMU=y
CONFIG_VIRTUALIZATION=y

Actual support depends on hardware capabilities, bootloader configuration, firmware components, and kernel implementation.

Build

Samsung provides the source for development and GPL compliance purposes.

Build instructions may vary depending on toolchain and environment.

Example:

./build_kernel_GKI.sh

Disclaimer

This repository is provided for development, research, and educational purposes.

The maintainer does not guarantee compatibility with modified kernels, custom recoveries, virtualization projects, or third-party software.

Credits

- Samsung Open Source Release Center
- Qualcomm Technologies
- Linux Kernel Community
- Android Open Source Project (AOSP)

Repository Maintainer

Hichem299
