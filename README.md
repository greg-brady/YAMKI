# YAMKI
Yet Another macOS KVM Installer (YAMKI)

This project seeks to provide simple setup of the latest version of macOS, Big Sur, as a KVM Virtual Machine.

This is based on the myriad of other projects with a similar goal:
  Foxlet: https://github.com/foxlet/macOS-Simple-KVM
  Kholia: https://github.com/kholia/OSX-KVM

I started using Foxlet's scripts, which are fantastic, but found that they were not compatible with Big Sur and the repository did not appear to be very active at the moment. Kholia's project is much more active. This project will not provide support for older versions of macOS.

Binary Blobs
This project uses binary blobs for Tianocore (https://github.com/tianocore/tianocore.github.io). OVMF_CODE-ure-efi.fd and OVMF_VARS-pure-efi-fd are included in their compiled form for simplicity. As of 27 Nov 2020, they are the based on the latest version of EDK II. There are no changes to this code to allow macOS to run. If you prefer, you can compile these yourself (https://github.com/tianocore/tianocore.github.io/wiki/How-to-run-OVMF) or download pre-built images (https://www.kraxel.org/repos/). 
