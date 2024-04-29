# Useful commands

```powershell
netsparkle-generate-appcast -a '.' -e msi -b '.' -o windows -u 'https://github.com/SHIROKEY/pelvic-training/releases/download/v0.6.7' -n 'Pelvic Training Application' --key-path '.' --reparse-existing --file-extract-version
```
> Note: It's uncertain why, but currently downloading from GitHub releases is not working so `https://github.com/SHIROKEY/pelvic-training/releases/download/v0.6.7` that link is not working. For now it's better to use LFS `https://github.com/SHIROKEY/pelvic-training/raw/main`
  