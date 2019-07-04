# resolve-linux-amd
Support in Ubuntu Linux for DavinciResolve with AMD GPU's

Davinci Resolve only supports NVIDIA CUDA GPU's out the box, for AMD gpu's you are either required to install the AMDGPU-PRO drivers, or use ROCM instead.

Those packages are supposed to grab the supported rocm repository, add yourself to the video group and installs the required udev rules

# Warning - Highly experimental packages, use those at your own risks. 

Read the Wiki instead to know how to install the support.
https://github.com/Lukypie/resolve-linux-amd/wiki

## Todo List
- [ ] Possibily fix all the eventual problems with the preiinst/postrm scripts if they break the Debian packaging reference
- [ ] Possibily fix all the eventual apt issues and conflicts when the packages are removed/installed/upgraded, I don't know if I already covered all the cases in my scripts. 
- [ ] Add the GPG key instead of workarounding with [trusted=yes]
