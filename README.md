# dotfiles

Minimal and professional Zsh environment setup for macOS, tailored for developers working on automation, cybersecurity, and productivity tooling.

> Maintained by Abraham Pisabarro Gallego. Public setup used daily on a MacBook Air M4 (15-inch, 16 GB RAM, 256 GB SSD).

## 🧰 Features

- Shell: Zsh + Oh My Zsh
- Prompt: Powerlevel10k
- Plugins:
  - `zsh-autosuggestions`
  - `zsh-syntax-highlighting`
- Fonts: MesloLGS Nerd Font (auto-installed)
- Includes clean `.zshrc`, `.p10k.zsh`, and optional aliases
- Git global name configured (email excluded for privacy)
- Designed for macOS developers (tested on Apple Silicon)

## 🚀 Quick Setup

Clone the repository and run the script:

```bash
git clone https://github.com/abrahampisabarro/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
bash 00-setup.sh

## 📁 Repository Structure

dotfiles/
├── 00-setup.sh          # Full setup script
├── zsh/
│   ├── .zshrc           # Shell configuration
│   ├── .p10k.zsh        # Powerlevel10k theme settings
│   └── .aliases         # Optional custom aliases (not yet active)
├── fonts/               # Optional font resources
└── README.md            # This file

## 📝 Notes

- Font is installed directly into `~/Library/Fonts/`
- `~/.zshrc` and `~/.p10k.zsh` will be symlinked
- No global email is set to protect privacy

---

## 💡 Recommended Use

Ideal for clean setups on new macOS environments, especially for security engineers, automation specialists, and CLI-based developers.

---

🛠 ️ Built by Abraham Pisabarro Gallego.
