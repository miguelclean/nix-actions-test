If using the dynamically linked binary release, remember to patch the ELF file accordingly to your distro: 
Example: patchelf --set-interpreter "$(cat $NIX_CC/nix-support/dynamic-linker)" hello
