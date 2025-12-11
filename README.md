# 🐧 Arch Linux Terminal Emulator

A fully-featured Arch Linux terminal emulator that runs entirely in your browser. Experience the power of Arch Linux with a realistic terminal interface, package management, and 150+ working commands including the complete Kali Linux security toolkit.

![Terminal Preview](https://img.shields.io/badge/Arch-Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Made with](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-orange?style=for-the-badge)
![Tools](https://img.shields.io/badge/Tools-150%2B-green?style=for-the-badge)

## ✨ Features

### 🖥️ Realistic Terminal UI
- Authentic macOS-style window with traffic light buttons
- JetBrains Mono monospace font
- Arch Linux blue color scheme
- Dynamic prompt showing `user@host:path$`
- Scrollable output with custom scrollbar

### 📁 Virtual File System
- Complete Linux directory structure (`/home`, `/etc`, `/usr`, `/var`, etc.)
- Navigable directories with `cd`, `ls`, `pwd`
- Create files and directories with `touch` and `mkdir`
- View file contents with `cat`
- Real configuration files (`.bashrc`, `pacman.conf`, etc.)

### 📦 Working Package Manager
- **`pacman -S <package>`** - Install packages with animated progress
- **`pacman -R <package>`** - Remove packages
- **`pacman -Ss <query>`** - Search available packages
- **`pacman -Q`** - List installed packages
- **`pacman -Syu`** - System upgrade simulation

### ⌨️ Interactive Features
- **Command History** - Use ↑/↓ arrow keys
- **Tab Completion** - Auto-complete commands
- **Ctrl+L** - Clear screen
- **Ctrl+C** - Cancel current input
- Click anywhere to focus input

---

## 🛠️ Built-in Commands

### Navigation
| Command | Description |
|---------|-------------|
| `ls [-la]` | List directory contents |
| `cd <dir>` | Change directory |
| `pwd` | Print working directory |

### File Operations
| Command | Description |
|---------|-------------|
| `cat <file>` | Display file contents |
| `touch <file>` | Create empty file |
| `mkdir <dir>` | Create directory |
| `rm <file>` | Remove file |
| `cp <src> <dst>` | Copy file |
| `mv <src> <dst>` | Move file |

### System Information
| Command | Description |
|---------|-------------|
| `neofetch` | Display system info with ASCII art |
| `uname -a` | Kernel information |
| `whoami` | Current user |
| `hostname` | System hostname |
| `date` | Current date/time |
| `uptime` | System uptime |
| `free` | Memory usage |
| `df` | Disk usage |
| `ps` | Running processes |
| `top` | Process viewer |

### Utilities
| Command | Description |
|---------|-------------|
| `echo <text>` | Print text |
| `clear` | Clear terminal |
| `history` | Command history |
| `env` | Environment variables |
| `export VAR=val` | Set variable |
| `alias` | Show aliases |
| `which <cmd>` | Locate command |
| `man <cmd>` | Manual page |
| `sudo <cmd>` | Run as root |
| `grep <pattern>` | Search text |

---

## 📦 Available Packages (150+)

### 💻 Development Tools
```bash
pacman -S nodejs      # Node.js + npm
pacman -S python      # Python 3 + pip
pacman -S rust        # Rust + cargo
pacman -S go          # Go programming language
pacman -S gcc         # GNU Compiler Collection
pacman -S git         # Version control
pacman -S docker      # Container platform
pacman -S code        # Visual Studio Code
```

### 🔧 System Utilities
```bash
pacman -S htop        # Interactive process viewer
pacman -S btop        # Modern resource monitor
pacman -S neofetch    # System info display
pacman -S tmux        # Terminal multiplexer
pacman -S zsh         # Z shell
pacman -S fish        # Friendly shell
```

### 🌐 Network Tools
```bash
pacman -S curl        # Data transfer
pacman -S wget        # File downloader
pacman -S nmap        # Network scanner
pacman -S nginx       # Web server
pacman -S openssh     # SSH tools
```

### 📝 Modern CLI Tools
```bash
pacman -S bat         # Better cat
pacman -S exa         # Better ls
pacman -S ripgrep     # Better grep
pacman -S fd          # Better find
pacman -S fzf         # Fuzzy finder
pacman -S jq          # JSON processor
```

### 🎮 Fun Commands
```bash
pacman -S sl          # Steam locomotive
pacman -S cowsay      # Speaking cow
pacman -S fortune     # Random quotes
pacman -S lolcat      # Rainbow text
pacman -S figlet      # ASCII art text
pacman -S cmatrix     # Matrix effect
```

---

## 🔐 Kali Linux Security Tools

### 🔍 Information Gathering
```bash
pacman -S nmap              # Network scanner
pacman -S maltego           # OSINT tool
pacman -S recon-ng          # Recon framework
pacman -S theharvester      # Email/subdomain harvester
pacman -S shodan            # Internet device search
pacman -S spiderfoot        # OSINT automation
pacman -S amass             # Attack surface mapping
pacman -S subfinder         # Subdomain discovery
pacman -S masscan           # Fast port scanner
pacman -S enum4linux        # SMB enumeration
pacman -S whatweb           # Web scanner
pacman -S wafw00f           # WAF detection
pacman -S dnsrecon          # DNS enumeration
pacman -S fierce            # DNS recon
```

### 🔓 Vulnerability Analysis
```bash
pacman -S nikto             # Web server scanner
pacman -S openvas           # Vulnerability scanner
pacman -S nessus            # Vulnerability scanner
pacman -S wpscan            # WordPress scanner
pacman -S sqlmap            # SQL injection tool
pacman -S nuclei            # Template scanner
pacman -S lynis             # System auditing
pacman -S trivy             # Container scanner
```

### 🌐 Web Application Testing
```bash
pacman -S burpsuite         # Web security testing
pacman -S zaproxy           # OWASP ZAP
pacman -S gobuster          # Directory brute-forcer
pacman -S dirb              # Web content scanner
pacman -S wfuzz             # Web fuzzer
pacman -S ffuf              # Fast web fuzzer
pacman -S feroxbuster       # Content discovery
pacman -S httpx             # HTTP toolkit
pacman -S katana            # Web crawler
```

### 🔑 Password Attacks
```bash
pacman -S john              # John the Ripper
pacman -S hashcat           # Password cracker
pacman -S hydra             # Login cracker
pacman -S medusa            # Brute-forcer
pacman -S cewl              # Wordlist generator
pacman -S crunch            # Wordlist generator
pacman -S ophcrack          # Rainbow tables
pacman -S hash-identifier   # Hash detection
```

### 📡 Wireless Attacks
```bash
pacman -S aircrack-ng       # WiFi security suite
pacman -S kismet            # Wireless detector
pacman -S wifite            # Automated WiFi audit
pacman -S reaver            # WPS attack
pacman -S bully             # WPS attack
pacman -S fern-wifi-cracker # WiFi cracker GUI
pacman -S fluxion           # Social engineering
```

### 💣 Exploitation Frameworks
```bash
pacman -S metasploit        # Exploitation framework
pacman -S beef-xss          # Browser exploitation
pacman -S exploitdb         # Exploit database
pacman -S setoolkit         # Social engineering
pacman -S crackmapexec      # Network tool
pacman -S evil-winrm        # WinRM shell
pacman -S impacket          # Network protocols
pacman -S sliver            # C2 framework
pacman -S covenant          # C2 framework
```

### 🕵️ Sniffing & Spoofing
```bash
pacman -S ettercap          # MITM attacks
pacman -S bettercap         # Network attacks
pacman -S responder         # LLMNR poisoner
pacman -S tcpdump           # Packet analyzer
pacman -S wireshark         # Protocol analyzer
pacman -S mitmproxy         # Intercepting proxy
pacman -S scapy             # Packet manipulation
pacman -S arpspoof          # ARP spoofing
pacman -S macchanger        # MAC changer
```

### 🚀 Post Exploitation
```bash
pacman -S mimikatz          # Credential harvesting
pacman -S empire            # Post-exploitation
pacman -S bloodhound        # AD graphing
pacman -S linpeas           # Linux privesc
pacman -S winpeas           # Windows privesc
pacman -S chisel            # Tunneling
pacman -S ligolo-ng         # Tunneling
```

### 🔬 Forensics
```bash
pacman -S autopsy           # Forensic platform
pacman -S binwalk           # Firmware analysis
pacman -S foremost          # File carving
pacman -S volatility        # Memory forensics
pacman -S sleuthkit         # File system forensics
pacman -S testdisk          # Data recovery
pacman -S exiftool          # Metadata reader
pacman -S steghide          # Steganography
pacman -S stegseek          # Stego cracker
```

### ⚙️ Reverse Engineering
```bash
pacman -S ghidra            # RE framework (NSA)
pacman -S radare2           # RE framework
pacman -S gdb               # GNU Debugger
pacman -S rizin             # RE framework
pacman -S cutter            # RE GUI
pacman -S apktool           # Android RE
pacman -S jadx              # Java decompiler
```

### ☁️ Cloud Security
```bash
pacman -S prowler           # Cloud security
pacman -S scoutsuite        # Cloud auditing
pacman -S pacu              # AWS exploitation
pacman -S cloudfox          # Cloud pentesting
```

---

## 🎯 Example Usage

### Basic System Usage
```bash
# Navigate the file system
cd /home/arch/projects
ls -la
cat hello.py

# Check system info
neofetch
uname -a
free
df
```

### Package Management
```bash
# Search for packages
pacman -Ss docker

# Install a package
pacman -S docker

# Use the installed package
docker ps
docker images

# List installed packages
pacman -Q

# Remove a package
pacman -R docker
```

### Security Testing Workflow
```bash
# Information gathering
pacman -S nmap
nmap -A target.com

# Web vulnerability scanning
pacman -S nikto
nikto -h http://target.com

# SQL injection testing
pacman -S sqlmap
sqlmap -u "http://target.com/page?id=1"

# Password cracking
pacman -S john
john --wordlist=passwords.txt hashes.txt

# Exploitation
pacman -S metasploit
msfconsole
```

### Fun Commands
```bash
pacman -S cowsay
cowsay "I use Arch btw"

pacman -S sl
sl

pacman -S figlet
figlet "Arch Linux"

# Built-in easter egg
btw
```

---

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Structure
- **CSS3** - Styling with custom terminal theme
- **JavaScript** - Terminal logic and command processing
- **Tailwind CSS** - Utility classes (via CDN)
- **JetBrains Mono** - Monospace font (via Google Fonts)

### Architecture
```
┌─────────────────────────────────────────────────────────┐
│                    Terminal UI                          │
├─────────────────────────────────────────────────────────┤
│  Command Input → Parser → Command Router                │
│                              ↓                          │
│              ┌───────────────┴───────────────┐         │
│              ↓                               ↓         │
│       Built-in Commands            Package Commands     │
│       (ls, cd, cat...)            (from installed)     │
│              ↓                               ↓         │
│       Virtual File System          Package Handlers     │
│              ↓                               ↓         │
│              └───────────────┬───────────────┘         │
│                              ↓                          │
│                      Output Display                     │
└─────────────────────────────────────────────────────────┘
```

### File System Structure
```
/
├── bin/          # Binary executables
├── boot/         # Boot files
├── dev/          # Device files
├── etc/          # Configuration files
│   ├── hostname
│   ├── hosts
│   └── pacman.conf
├── home/
│   └── arch/     # User home directory
│       ├── .bashrc
│       ├── .config/
│       ├── Documents/
│       ├── Downloads/
│       ├── Pictures/
│       ├── projects/
│       └── README.md
├── lib/          # Libraries
├── mnt/          # Mount points
├── opt/          # Optional packages
├── proc/         # Process info
├── root/         # Root home
├── tmp/          # Temporary files
├── usr/          # User programs
└── var/          # Variable data
```

---

## 📝 License

This project is open source and available under the MIT License.

---

## 🙏 Acknowledgments

- Inspired by Arch Linux and the Arch Wiki
- Kali Linux tools documentation
- The open-source security community

---

<div align="center">

**BTW, I use Arch. 🐧**

Made with ❤️ for the Linux community

</div>
