# FastResearch
Backend: FastAPI
FrontEnd: N/A

## Prerequisites

### Windows Setup

1. Install Chocolatey (Package Manager for Windows)
   - Open PowerShell as Administrator
   - Run the following command:
   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
   ```
   - Verify installation by running: `choco --version`

2. Install pyenv-win using Chocolatey
   - In the same PowerShell (Admin) window, run:
   ```powershell
   choco install pyenv-win
   ```
   - Restart your terminal
   - Verify installation by running: `pyenv --version`