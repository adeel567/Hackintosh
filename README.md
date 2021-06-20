# Hackintosh
EFI folder for my Skylake Hackintosh, currently on macOS Big Sur.

Once booted up, it is perfectly stable! (in my testing) 🥰


# Specs:
i7 6700k

MSI Z170-A Pro

GTX 1070 - not in use for macOS

HD 530 - current GPU, to be replaced after shortage (feelsbadman)

16GB DDR4

# Todo and Problems
- [x] Realtek audio 
- [x] Pretty UEFI
- [ ] FileVault - easy to fix
- [ ] USB patch - back 2x USB do not work at this moment
- [ ] Sleep - iGPU issue
- [ ] *Proper* dual-monitor support - iGPU issue
- [ ] DRM - iGPU issue
- [ ] iMessage, iCloud - not a priority imo


However, the major problem is that the iGPU is not properly supported. I've played around with the framebuffer patching quite a bit and single-display works, but for dual-display I boot with both monitors attached, then reattach with DVI, followed by DP and it somehow works. Sleep functionality due to the iGPU is also broken permanently. 

# IMPORTANT!!! #
You should build the EFI yourself, mine should only be used as a sanity check, even if our hardware is identical. Please follow the OpenCore guide. Also note I've scubbed my serial number, which can be generated if you follow the aforementioned guide...
