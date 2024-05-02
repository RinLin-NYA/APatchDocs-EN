# What is APatch?

APatch is a **kernel-based** root solution for Android devices that works in kernel mode and grants root privileges to user space apps directly in kernel space.

## Features

Compatible with most Android devices, not just limited to devices with GKI kernel.

Supports APModule (APM) similar to Magisk modules.

Supports KPModule (KPM), which allows to inject any code into kernel (Requires kernel function `inline-hook` and `syscall-table-hook` enabled).

APatch depends on KernelPatch.

The APatch UI and the APModule source code have been derived and modified from KernelSU.

## How to use APatch?

Please read this: [Installation](/en/install)

## How to patch?

Please read this: [Patch](/en/patch)