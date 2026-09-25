# ESS ADK — One-Shot Installer

A single command that installs everything needed for the ESS Maker Kit: VS Code, Python 3.12, Git, GitHub CLI, the .NET runtime, NuGet, Copilot extensions, pip dependencies, and clones the repo.

**Windows** (PowerShell):

```powershell
iex (irm https://raw.githubusercontent.com/microsoft/Employee-Self-Service-Agent-Developer-Kit/main/setup/bootstrap.ps1)
```

**macOS** (Terminal):

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/microsoft/Employee-Self-Service-Agent-Developer-Kit/main/setup/bootstrap-mac.sh)"
```

See [`setup/README.md`](setup/README.md) for FlightCheck-only, Codespaces, manual setup, and mode-specific bootstraps. See [SUPPORT.md](SUPPORT.md), [SECURITY.md](SECURITY.md), [CONTRIBUTING.md](CONTRIBUTING.md), and [LICENSE](LICENSE).
