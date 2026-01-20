# Command-Line Quick Reference

A condensed cheat sheet of essential commands for **Windows**, **Linux**, and **macOS**.  
Perfect for CompTIA A+ exam prep and real-world troubleshooting.

---

## 🖥️ Windows

| Category        | Command              | Purpose                                |
|-----------------|----------------------|----------------------------------------|
| Networking      | `ipconfig /all`      | Show IP configuration details          |
|                 | `ping <address>`     | Test connectivity                      |
|                 | `tracert <address>`  | Trace route to destination             |
|                 | `nslookup <domain>`  | DNS lookup                             |
| System          | `sfc /scannow`       | Scan and repair system files           |
|                 | `chkdsk /f`          | Check and fix disk errors              |
|                 | `tasklist`           | List running processes                 |
|                 | `diskpart`           | Manage partitions                      |
| Security        | `net user`           | Manage user accounts                   |
|                 | `icacls <file>`      | View/set file permissions              |
|                 | `attrib +h <file>`   | Hide file                              |
| Troubleshooting | `eventvwr`           | Open Event Viewer                      |
|                 | `msconfig`           | Manage startup options                 |
|                 | `driverquery`        | List installed drivers                 |

---

## 🐧 Linux

| Category        | Command                  | Purpose                                |
|-----------------|--------------------------|----------------------------------------|
| Networking      | `ip addr`                | Show IP addresses                      |
|                 | `ping <address>`         | Test connectivity                      |
|                 | `netstat -tuln`          | Show listening ports                   |
|                 | `dig <domain>`           | DNS lookup                             |
| System          | `top`                    | Monitor processes                      |
|                 | `ps aux`                 | List processes                         |
|                 | `df -h`                  | Disk usage                             |
|                 | `journalctl -xe`         | View logs                              |
| Security        | `chmod 755 <file>`       | Change permissions                     |
|                 | `chown user:group <file>`| Change ownership                       |
|                 | `sudo <command>`         | Run as root                            |
|                 | `ufw enable`             | Enable firewall                        |
| Troubleshooting | `dmesg | less`           | Kernel messages                        |
|                 | `tail -f /var/log/syslog`| Live log view                          |
|                 | `grep "error" file.log`  | Search logs                            |
|                 | `systemctl status <svc>` | Service status                         |

---

## 🍎 macOS

| Category        | Command                                         | Purpose                                |
|-----------------|-------------------------------------------------|----------------------------------------|
| Networking      | `networksetup -listallhardwareports`            | Show interfaces                        |
|                 | `ping <address>`                                | Test connectivity                      |
|                 | `traceroute <address>`                          | Trace route                            |
| System          | `system_profiler`                               | System info                            |
|                 | `pmset -g`                                      | Power management settings              |
|                 | `diskutil list`                                 | Show disks                             |
| Troubleshooting | `log show --predicate 'eventMessage contains "error"'` | Search logs                     |
|                 | `fsck -fy`                                      | File system check                      |
|                 | `csrutil status`                                | SIP status                             |

---

## 📝 Notes
- Commands are grouped by **Networking**, **System**, **Security**, and **Troubleshooting**.  
- Use this sheet for **fast recall** during exams or real-world IT support.  
