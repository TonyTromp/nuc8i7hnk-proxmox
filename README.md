"# nuc8i7hnk-proxmox" 

My Proxmox settings for running the Hades Canyon with GPU Passthrough.

NOTE: When using ZFS in Raid, grub is not beeing using, so update the ```/etc/kernel/cmdline``` and run
```proxmox-boot-tool refresh```