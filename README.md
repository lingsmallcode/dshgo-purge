# dshgo tools

Dev-side installer and asset scripts for the DSH Android (proot) environment.

## Install

```bash
curl -fsSL https://github.com/lingsmallcode/dshgo-purge/releases/latest/download/install.sh | bash
```

Fully self-adaptive: works on fresh environments without curl, falls back to
wget / python3 and mirrors automatically. Restart the app and start a new session after install.

## Notes
- 0 runtime dependencies on the target device
- Host compatibility: dsh 0.2.2-rc.1 through rc.3
