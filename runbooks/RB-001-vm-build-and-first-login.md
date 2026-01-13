### RB-001 - VM Build and First Login (VirtualBox + Ubuntu) ###

## Purpose
- Rebuild my Ubuntu VM from scratch and fix common boot issues

## Symptoms this runbook covers
- Missing OS
- Black screen/ Boot loop
- No internet in VM
- Commands missing (ex: git not found)

## Fast checks (do in order)
1) Storage: Is the Ubuntu ISO attached
2) Boot order: Optical first for install; Hard Disk first after install.
3) Disk: Is a virtual disk attached (SATA Port 0)?
4) EFI: on/off (match what you used during install)

## Build steps

# 1) download ISO
- ISO File Name:
- Where saved:

# 2) create VM
- OS Type:
- RAM: 
- CPU: 
- Disk size:
- Video Memory:

# 3) attach ISO
- VirtualBox -> Settings -> Storage -> Optical Drive -> Choose disk file -> select ISO

# 4) install Ubuntu
- Username:
- Password:
- Disk install option:


## Verification checklist ( proof it works )
- VM boots to desktop/login
- Terminal works: `uname  -a`
- Folder navigation: `pwd`, `ls`, `cd`
- Internet: `ping -c 2 1.1.1.1` and `ping -c 2 google.com`
- Git: `git --version`

## Prevention (avoid breaking it)
- Snapshot name + when taken:
- What changes require a new snapshot:
