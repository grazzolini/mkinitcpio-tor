# mkinitcpio-tor
Arch Linux mkinitcpio hook for running tor on the initramfs

This hook allows running tor on the initramfs, mostly for remote unlocking, in situations where
the server does not have direct connectivity or the user wants to conceal the fact a server has
the remote unlocking functionality.

It uses whatever is configured on the actual system, so if the hidden service works on the root
system, it should work on the initramfs as well.
