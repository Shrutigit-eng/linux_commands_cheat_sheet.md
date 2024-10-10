# linux_commands_cheat_sheet.md
# Linux Commands Cheat Sheet

### Basic Commands
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `pwd`                  | Print working directory                        |
| `ls`                   | List directory contents                        |
| `cd [directory]`       | Change directory                               |
| `mkdir [directory]`    | Create a new directory                         |
| `rmdir [directory]`    | Remove a directory (must be empty)             |
| `rm [file]`            | Remove a file                                  |
| `cp [source] [destination]` | Copy file or directory                  |
| `mv [source] [destination]` | Move file or directory                  |
| `touch [file]`         | Create an empty file                           |
| `cat [file]`           | Display file contents                          |
| `echo [text] > [file]` | Write text to file                             |

### File Permissions
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `chmod [permissions] [file]` | Change file permissions                |
| `chown [user]:[group] [file]` | Change file owner and group           |
| `ls -l`                | List files with permissions                    |

### File Management
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `find [path] -name [file]` | Search for files by name                  |
| `grep [pattern] [file]`| Search for a pattern in a file                 |
| `tar -cvf [archive.tar] [directory]` | Create a tarball (archive)     |
| `tar -xvf [archive.tar]` | Extract a tarball                           |
| `zip [file.zip] [files]` | Compress files into a zip archive           |
| `unzip [file.zip]`     | Extract files from a zip archive               |

### Disk Usage
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `df -h`                | Display disk space usage in human-readable form|
| `du -sh [directory]`   | Display directory size                         |
| `mount`                | Mount a filesystem                             |
| `umount [mount_point]` | Unmount a filesystem                           |

### Networking
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `ifconfig`             | Display network interface information          |
| `ping [host]`          | Ping a host                                    |
| `netstat -tuln`        | List listening ports                           |
| `curl [URL]`           | Fetch a webpage                                |
| `wget [URL]`           | Download files from the web                    |

### Process Management
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `ps aux`               | List all running processes                     |
| `top`                  | Display real-time system processes             |
| `kill [PID]`           | Terminate a process by PID                     |
| `killall [process_name]`| Terminate all processes by name               |
| `htop`                 | Interactive process viewer (if installed)      |

### System Information
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `uname -a`             | Display kernel version and system architecture |
| `hostname`             | Display or set the system hostname             |
| `uptime`               | Show how long the system has been running      |
| `free -h`              | Display memory usage                           |
| `df -h`                | Display disk space usage                       |

### Package Management
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `apt-get update`       | Update package list (Debian/Ubuntu)            |
| `apt-get upgrade`      | Upgrade installed packages (Debian/Ubuntu)     |
| `yum update`           | Update packages (RedHat/CentOS)                |
| `yum install [package]`| Install a package (RedHat/CentOS)              |
| `dpkg -i [package.deb]`| Install a .deb package                         |
| `rpm -i [package.rpm]` | Install a .rpm package                         |

### User Management
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `adduser [username]`   | Add a new user                                 |
| `passwd [username]`    | Change user password                           |
| `deluser [username]`   | Delete a user                                  |
| `usermod -aG [group] [username]` | Add user to a group                 |

### SSH & File Transfer
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `ssh [user]@[host]`    | Connect to a host via SSH                      |
| `scp [file] [user]@[host]:[path]` | Copy file to a remote host via SCP |
| `rsync -avz [source] [user]@[host]:[path]` | Sync files between local and remote |

### System Logs
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `tail -f [file]`       | View the last lines of a file in real-time     |
| `dmesg`                | Print kernel ring buffer messages              |
| `journalctl -xe`       | View systemd logs                              |

### Text Editors
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `nano [file]`          | Open file in nano editor                       |
| `vim [file]`           | Open file in vim editor                        |
| `gedit [file]`         | Open file in graphical editor (GUI)            |

### Miscellaneous
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `history`              | Show command history                           |
| `alias ll='ls -la'`    | Create a shortcut for a command                |
| `clear`                | Clear the terminal screen                      |

---

This cheat sheet covers essential Linux commands for file management, networking, user management, and more.
