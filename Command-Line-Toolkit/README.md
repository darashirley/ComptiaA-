# Command-Line Toolkit

A structured library of essential command-line tools for **Windows**, **Linux**, and **macOS**.  
Designed for **CompTIA A+ exam prep** and **real-world IT troubleshooting**.

---

## 📚 Contents

- [Overview](#overview)
- [Windows Commands](#windows-commands)
- [Linux Commands](#linux-commands)
- [macOS Commands](#macos-commands)
- [Cheat Sheets](#cheat-sheets)
- [Contributing](#contributing)

---

## Overview

This repository organizes commands by **platform** and **category** (Networking, System, Security, Troubleshooting).  
Each entry includes:
- Command syntax
- Common switches
- Example usage
- Sample output
- When to use it (exam + real-world context)

---

## Windows Commands

### Networking
- `ipconfig /all` → View IP configuration details  
- `ping <address>` → Test connectivity  
- `tracert <address>` → Trace route to destination  
- `nslookup <domain>` → DNS lookup  

### System
- `sfc /scannow` → Scan system files  
- `chkdsk /f` → Check and repair disk  
- `tasklist` → List running processes  
- `diskpart` → Manage partitions  

### Security
- `net user` → Manage user accounts  
- `icacls <file>` → View/set file permissions  
- `attrib +h <file>` → Hide file  

### Troubleshooting
- `eventvwr` → Open Event Viewer  
- `msconfig` → Manage startup options  
- `driverquery` → List installed drivers  

---

## Linux Commands

### Networking
- `ip addr` → Show IP addresses  
- `ping <address>` → Test connectivity  
- `netstat -tuln` → Show listening ports  
- `dig <domain>` → DNS lookup  

### System
- `top` → Monitor processes  
- `ps aux` → List processes  
- `df -h` → Disk usage  
- `journalctl -xe` → View logs  

### Security
- `chmod 755 <file>` → Change permissions  
- `chown user:group <file>` → Change ownership  
- `sudo <command>` → Run as root  
- `ufw enable` → Enable firewall  

### Troubleshooting
- `dmesg | less` → Kernel messages  
- `tail -f /var/log/syslog` → Live log view  
- `grep "error" file.log` → Search logs  
- `systemctl status <service>` → Service status  

---

## macOS Commands

### Networking
- `networksetup -listallhardwareports` → Show interfaces  
- `ping <address>` → Test connectivity  
- `traceroute <address>` → Trace route  

### System
- `system_profiler` → System info  
- `pmset -g` → Power management settings  
- `diskutil list` → Show disks  

### Troubleshooting
- `log show --predicate 'eventMessage contains "error"'` → Search logs  
- `fsck -fy` → File system check  
- `csrutil status` → SIP status  

---

## Cheat Sheets

- [Quick Reference](#quick-reference.md) 
- **Flowcharts**: Visual troubleshooting paths (e.g., boot issues, network failures)  

---

## Contributing

Contributions are welcome!  
- Fork the repo  
- Add new commands or scenarios  
- Submit a pull request  

---

## License

MIT License – free to use and share.
