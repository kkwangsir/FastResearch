# UV - Fast Python Package Manager

UV is a fast and reliable Python package manager, up to 10-100x faster than pip.

## Quick Windows Installation

```powershell
curl -LsSf https://astral.sh/uv/install.ps1 | powershell
```

## Basic Usage

1. Create and activate virtual environment:
```powershell
uv venv
.venv/Scripts/activate
```

2. Package management commands:
```powershell
# Install packages
uv add package_name
uv add package1 package2          # Install multiple packages
uv add fastapi==0.109.0          # Install specific version

# Upgrade packages
uv upgrade package_name

# Remove packages
uv remove package_name

# Install from requirements.txt
uv pip sync requirements.txt

# Generate requirements.txt
uv pip freeze > requirements.txt
```

3. Python version management:
```powershell
uv python list                    # List available versions
uv python install 3.12         # Install specific version
uv python default 3.12         # Set default version
```

## Common Features

- Create virtual environment with specific Python version:
```powershell
uv venv -p 3.12
```

## Key Features

- 10-100x faster than pip
- Fully pip compatible
- Built-in virtual environment management
- Reliable dependency resolution
- Cache-first architecture
