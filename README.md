# Hackintosh
EFI folder for my Skylake Hackintosh, currently on macOS Big Sur.


# Specs:
i7 6700k

MSI Z170-A Pro

GTX 1070 - not in use for macOS

HD 530 - current GPU, to be replaced after shortage (feelsbadman)

16GB DDR4

# Problems:
I still have to patch the USBs and setup FileVault. However, the major problem is that the iGPU is not properly supported. I've played around with the framebuffer patching quite a bit and single-display works, but for dual-display I boot with both monitors attached, then reattach with DVI, followed by DP and it somehow works. Sleep functionalitu due to the iGPU is also broken.

# IMPORTANT!!! #
You should build the EFI yourself, mine should only be used as a sanity check, even if our hardware is identical. Please follow the OpenCore guide.
