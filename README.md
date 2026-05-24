<p align="center">
  <img src="kiro.jpg" alt="Kiro" width="220" />
</p>

# edu-surfn-numixs-blue

Blue variant of the **Surfn Numixs** icon theme — a Numix-derived icon set with Surfn-style folder icons. Part of the `~/EDU/` icon-theme series.

## What's in this repo

- `surfn-icons/Surfn-Numixs-Blue/` — the icon theme assets (note: at repo root, not under `usr/share/icons/`).
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-surfn-numixs-blue
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-surfn-numixs-blue.git
cd edu-surfn-numixs-blue
sudo cp -r surfn-icons/Surfn-Numixs-Blue /usr/share/icons/
sudo gtk-update-icon-cache -f /usr/share/icons/Surfn-Numixs-Blue
```

### Activate

```bash
gsettings set org.gnome.desktop.interface icon-theme "Surfn-Numixs-Blue"
```

The repo ships a `create-new-icon-theme.cache.sh` helper inside the theme folder for rebuilding the icon cache after edits.

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

<!-- KIRO-FUNDING-FOOTER:START — managed by Kiro-HQ/cascade-readme-footer.sh -->
## Help fund Kiro

Everything I build here stays free and open — always. If Kiro or any of these
tools have ever saved you time or taught you something, a small monthly
contribution helps keep the work going. Donations target break-even, nothing
more — the core always stays free for everyone.

- GitHub Sponsors: https://github.com/sponsors/erikdubois
- Patreon: https://www.patreon.com/c/kiroproject
- YouTube memberships: https://www.youtube.com/@ErikDubois/join
- Ko-fi: https://ko-fi.com/erikdubois
- PayPal: https://www.paypal.me/erikdubois
<!-- KIRO-FUNDING-FOOTER:END -->

## License

See [LICENSE](./LICENSE).
