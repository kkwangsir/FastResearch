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

2. Install Required Tools
   ```powershell
   # Install Make
   choco install make
   
   # Install Git Bash
   choco install git.install
   
   # Verify installations
   make --version
   git --version
   ```

3. Python Package Management
   - For information about installing Python and managing packages using UV (fast Python package manager), see [UV Package Manager](docs/uv/uv.md)