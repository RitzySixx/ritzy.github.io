# Ritzy's Forensic Tools

![Project Banner](https://i.imgur.com/JZQZQZQ.png)

A comprehensive collection of professional digital forensics and security analysis utilities designed to help investigators uncover critical evidence and analyze system artifacts.

## Features

- **Advanced Analysis**: Deep dive into system artifacts with precision tools
- **Efficient Tools**: Optimized utilities that deliver fast results
- **Security Focused**: Developed with security best practices
- **Cross-Platform**: Tools available for Windows and PowerShell environments
- **Easy to Use**: Intuitive interface with clear documentation

## Available Tools

| Tool | Version | Description | Download |
|------|---------|-------------|----------|
| Service Execution Analyzer | v1.1.5 | Analyze process memory for forensic artifacts | [Download](https://github.com/ritzysixx/Process-Executions/releases/download/V1.1.5/ProcessMemoryScanner.exe) |
| Registry Executions Scanner | v1.2.0 | Scan registry for execution artifacts | [Download](https://github.com/ritzysixx/Registry-Executions/releases/download/Executions/Registry.Executions.exe) |
| DMA Device Detector | v1.0.0 | Detect DMA-capable devices (PowerShell) | [Download](https://github.com/ritzysixx/dma-catcher/releases/download/V1.0.0/DMA.Catcher.ps1) |
| Timeline Explorer | v2.0.0.1 | Visualize timeline data for forensic analysis | [Download](https://download.ericzimmermanstools.com/net6/TimelineExplorer.zip) |
| Network Traffic Analyzer | Coming Soon | Analyze network traffic patterns | - |
| Memory Imager Pro | Coming Soon | Professional memory acquisition tool | - |
| Advanced File Carver | Coming Soon | Recover deleted files and artifacts | - |
| Hash Analyzer Pro | Coming Soon | File hashing and verification tool | - |

## Getting Started

### Prerequisites
- Windows 7/Server 2008 or newer
- .NET Framework 4.8 (for some tools)
- Administrator privileges
- PowerShell 5.1+ (for PowerShell tools)

### Installation
1. Download the desired tool from the table above
2. For executables: Run as Administrator
3. For PowerShell scripts: 
   ```powershell
   Set-ExecutionPolicy RemoteSigned
   .\ScriptName.ps1
