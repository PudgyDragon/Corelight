#Write-up in Progress

# Corelight Sensor on Proxmox
### Advisory
Please note, I haven't been able to do a fresh install using Corelight's initial OVA files. This is because they use a seeding process that requires the use of ESXi. Unfortunately (in this scenario) they encrypt their drives and only Corelight Support has root access, so it's not really possible to seed it without using ESXi (that I'm aware of). With that said, once you create a VM with ESXi, you are able to migrate it really easily over to Proxmox.
