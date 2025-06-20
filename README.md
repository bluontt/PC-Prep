# BluXploit PC Prep

[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/BluXploit/PC-Prep)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/BluXploit/PC-Prep)
[![Gaming](https://img.shields.io/badge/Gaming-Optimized-00D4AA?style=for-the-badge&logo=steam&logoColor=white)](https://github.com/BluXploit/PC-Prep)

> **A Windows security checker and gaming optimization tool designed for peak performance**

![BluXploit PC Prep Screenshot](https://via.placeholder.com/800x400/1a202c/22d3ee?text=BluXploit+PC+Prep+Terminal)

## 🎯 What is BluXploit PC Prep?

BluXploit PC Prep is a Windows security assessment and gaming optimization tool that helps you identify and configure system settings for maximum gaming performance. Built by Blu Services, this tool provides both a sleek web interface and a powerful command-line version with retro terminal aesthetics.

### ✨ Key Features

- **🔍 Comprehensive Security Scanning** - Checks 8+ critical Windows security features
- **🎮 Gaming-Optimized Results** - Color-coded recommendations for gaming performance
- **🚀 Standalone Executable** - No Node.js installation required for end users
- **🎨 Retro Terminal Design** - Beautiful ASCII art and cyan color scheme
- **⚡ Fast & Lightweight** - Minimal system resource usage

## 🛡️ Security Features Monitored

| Feature | Description | Gaming Impact |
|---------|-------------|---------------|
| **Virtualization (VT-x/AMD-V)** | Hardware virtualization support | Required for some games |
| **Hyper-V** | Microsoft's hypervisor platform | Can cause gaming performance issues |
| **Secure Boot** | UEFI security feature | Generally safe for gaming |
| **Core Isolation (HVCI)** | Hardware-based security | May impact gaming performance |
| **Vulnerable Driver Blocklist** | Blocks known malicious drivers | Recommended security feature |
| **Real-Time Protection** | Windows Defender scanning | Can cause FPS drops in games |
| **Visual C++ Redistributable** | Runtime libraries for games | Essential for most games |
| **Riot Vanguard** | Anti-cheat system | Required for Valorant |

## 🚀 Quick Start

Download Executable (Recommended)
1. Download the latest `bluxploit-pc-prep.exe` from [Releases](https://github.com/BluXploit/PC-Prep/releases)
2. Run the executable - no installation required!
3. Follow the on-screen recommendations


### Command Line Interface
```
$$$$$$$\  $$\                 $$$$$$\                              $$\                              
$$  __$$\ $$ |                $$  __$$\                             \__|                             
$$ |  $$ |$$ |$$\   $$\       $$ /  \__|$$$$$$\  $$$$$$\ $$\    $$\ $$\  $$$$$$$\  $$$$$$\   $$$$$$$\ 
$$$$$$$\ |$$ |$$ |  $$ |      \$$$$$$\  $$  __$$\$$  __$$\\$$\  $$  |$$ |$$  _____|$$  __$$\ $$  _____|
$$  __$$\ $$ |$$ |  $$ |       \____$$\ $$$$$$$$ |$$ |  \__|\$$\$$  / $$ |$$ /      $$$$$$$$ |\$$$$$$\  
$$ |  $$ |$$ |$$ |  $$ |      $$\   $$ |$$   ____|$$ |      \$$$  /  $$ |$$ |      $$   ____| \____$$\ 
$$$$$$$  |$$ |\$$$$$$  |      \$$$$$$  |\$$$$$$$\ $$ |       \$  /   $$ |\$$$$$$$\ \$$$$$$$\ $$$$$$$  |
\_______/ \__| \______/        \______/  \_______|\__|        \_/    \__| \_______| \_______|\_______/ 

🔒 BluXploit PC Prep - System Optimization Tool
```

## 🎯 Understanding the Results

### Color Coding System
- **🟢 Green (Disabled)** - Optimal for gaming performance
- **🔴 Red (Enabled)** - May impact gaming performance
- **ℹ️ Blue (Info)** - Informational status

### Gaming Recommendations
- **Disable Hyper-V** for better gaming performance
- **Disable Core Isolation** if experiencing FPS issues
- **Keep Real-Time Protection** enabled but add game exclusions
- **Enable Virtualization** for compatibility with some games

## 🛠️ Technical Details

### Built With
- **TypeScript** - Type-safe development
- **Node.js** - Runtime environment
- **Chalk** - Terminal styling
- **Execa** - Process execution
- **CLI Progress** - Progress bars

### System Requirements
- Windows 10/11 (64-bit)
- Administrator privileges (for some checks)
- No additional software required for executable version

### Architecture
```
BluXploit PC Prep/
├── Web Interface (HTML/CSS/JS)
├── CLI Tool (TypeScript/Node.js)
├── Security Checks (PowerShell Integration)
└── Executable Build (PKG)
```

## 🤝 Community & Support

### Join Our Community
- 💬 **Discord**: [https://discord.gg/BPgmN3paJV](https://discord.gg/BPgmN3paJV)
- 📱 **Telegram**: @BluXploit
- 🐙 **GitHub**: [@BluXploit](https://github.com/BluXploit)

### Getting Help
1. Check the [Issues](https://github.com/BluXploit/PC-Prep/issues) page
2. Join our Discord for real-time support
3. Create a new issue with detailed information

## 📋 Roadmap

- [ ] **GPU Optimization Checks** - NVIDIA/AMD driver optimizations
- [ ] **Network Optimization** - Gaming network settings
- [ ] **Storage Analysis** - SSD health and game storage optimization
- [ ] **Process Monitoring** - Real-time system resource usage
- [ ] **Auto-Fix Mode** - One-click optimization
- [ ] **Gaming Profiles** - Per-game optimization settings

## 🔧 Development

### Prerequisites
- Node.js 18+
- TypeScript 5.0+
- Windows 10/11 (for testing PowerShell commands)

### Development Commands
```bash
# Install dependencies
npm install

# Run in development mode
npm run dev

# Build TypeScript
npm run build

# Create Windows executable
npm run dist

# Run security checks
npm run security-check
```

### Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

BluXploit PC Prep is designed to help optimize your gaming experience. Always create system restore points before making significant changes to your Windows configuration. The developers are not responsible for any system modifications you choose to make based on this tool's recommendations.

---

<div align="center">

**Made with ❤️ by [Blu Services](https://discord.gg/BPgmN3paJV)**

*Optimizing Windows for peak gaming performance*

</div>