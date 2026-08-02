

# Install Ollama on Windows

Follow the steps below to download and install **Ollama** on Windows.

## Prerequisites

- Windows 10 (22H2 or later) or Windows 11
- PowerShell
- Internet connection

## Installation

1. Open **PowerShell**.
2. Run the following command:

```powershell
irm https://ollama.com/install.ps1 | iex
```

3. Wait for the installation to complete.
4. Verify the installation:

```powershell
ollama --version
```

## Alternative: Download the Installer

If you prefer using the graphical installer, download it from the official Ollama website:

https://ollama.com/download/windows

## Official Documentation

For more information, visit:

- https://ollama.com/download/windows
- https://github.com/ollama/ollama

---

**Note:** The `irm` command is a **PowerShell** command and will not work directly in Git Bash. If you're using Git Bash, either open PowerShell to run the installation command or invoke PowerShell from Git Bash:

```bash
powershell.exe -ExecutionPolicy Bypass -Command "irm https://ollama.com/install.ps1 | iex"
```
