# GitHub copy-and-paste guide

Download Ubuntu from [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop). Choose [single boot](INSTALL_SINGLE_BOOT.md), [dual boot](INSTALL_DUAL_BOOT.md), or [VMware](INSTALL_VMWARE.md).

Create a public repository named `curve-studio-os`, then in PowerShell in this folder run:

```powershell
git init
git add README.md apps.txt install.sh COPYRIGHTS.md INSTALL_SINGLE_BOOT.md INSTALL_DUAL_BOOT.md INSTALL_VMWARE.md GITHUB_GUIDE.md curve-studio.svg
git commit -m "Add Curve Studio OS setup"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/curve-studio-os.git
git push -u origin main
```

Replace `YOUR-USERNAME`. Never commit ISO files, secrets, private data, or proprietary binaries.

Include FEATURES.md and the complete features/ directory when copying this project to GitHub.

