# 🛡️ nosudopass

TUI tool to manage **sudo NOPASSWD** rules for users.
Allows enabling or disabling sudo without password via an interactive terminal menu.

![screen](./screen.png)

## Support
- OS: `Linux` (only)
- Architecture: `x86_64`, `aarch64`, `arm64`

## Install / Update

### Global

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/teplostanski/nosudopass/main/scripts/install.sh)" -- --global
```

> [!NOTE]
> If you get a `"Permission denied"` error, try running the command using `sudo`.

## 🚀 Run

```bash
sudo nosudopass
```

### Local (for current user)

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/teplostanski/nosudopass/main/scripts/install.sh)"
```

## 🚀 Run

```bash
sudo env PATH="$PATH" nosudopass
```
Or
```bash
sudo ~/.local/bin/nosudopass
```

## Uninstall

```bash
sudo sh -c "$(curl -fsSL https://raw.githubusercontent.com/teplostanski/nosudopass/main/scripts/uninstall.sh)"
```

## AI Assistance Disclosure

This project was developed with AI coding assistance. 
All generated code has been reviewed and modified by human developers.

<br>

<div>
  <a href="https://donate.teplostan.ski" target="_blank">
    <img src="https://src.teplostan.ski/support-the-project.svg" alt="Support The Project 🖤" />
  </a>
</div>
