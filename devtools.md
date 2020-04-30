- Docker
- Insomnia
- Chrome
- Slack
- OneNote

# Windows Setup
1. Enable Hyper_V
2. Install Boxstarter + NodeJs tools (https://github.com/Microsoft/windows-dev-box-setup-scripts)
3. Install WSL

# Boxstarter / Chocolatey Installs
```
cinst -y git.install 
cinst -y poshgit
cinst -y postman
cinst -y filezilla
cinst -y 7zip.install
cinst -y paint.net
cinst -y winmerge
cinst -y kdiff3
cinst -y visualstudiocode

Cinst -y markdownmonster
Set-WindowsExplorerOptions -EnableShowHiddenFilesFoldersDrives -EnableShowProtectedOSFiles -EnableShowFileExtensions
Disable-BingSearch
Enable-RemoteDesktop
Disable-UAC
```
