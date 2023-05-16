
<div align="center">
<img width="30%" src="./assets/catgorl.png">
</div>

<div align="center">
  <p></p>
  <p><b><i> ~ Minimalistic Dotfiles ~ </i></b></p>
  <img src="https://img.shields.io/github/last-commit/dynalar/dotfiles/mac-os?color=%23c4a7e7&style=for-the-badge">
  <img src="https://img.shields.io/github/repo-size/dynalar/dotfiles?color=%23e0def4&style=for-the-badge">
  <img src="https://img.shields.io/github/stars/dynalar/dotfiles?color=%23ebbcba&style=for-the-badge">
  <img src="https://img.shields.io/github/license/dynalar/dotfiles?color=%239ccfd8&style=for-the-badge">
</div>


| ![1](./assets/fetch.png) | ![2](./assets/fetch_3.png) |
| --- | --- |


### ***Table of Contents***

- **[Table of Contents](#table-of-contents)**
    - **[Screenshots](#screenshots)**
    - **[Environment](#environment)**
    - **[Themes](#theme-change-script)**
    - **[Dependencies](#dependencies)**

<!-- ### ***Screenshots*** <details>
<summary><b>Nord</b></summary>

| ![ThemeSelector](./assets/nord/theme-selector.png) | ![Nvim](./assets/nord/nvim.png) |
| --- | --- |
| ![Zathura](./assets/nord/zathura.png) | ![FileManager](./assets/nord/explorer.png) |

</details>

<details>
<summary><b>Rose Pine</b></summary>

| ![ThemeSelector](./assets/rose-pine/theme-selector.png) | ![Nvim](./assets/rose-pine/nvim.png) |
| --- | --- |
| ![Zathura](./assets/rose-pine/zathura.png) | ![FileManager](./assets/rose-pine/explorer.png) |

</details> -->

### ***Environment***

- **Distro**: Mac OS X
- **Compositor**: Quartz
- **Terminal**: iTerm 2
- **File Manager**: Finder
- **Editor**: NeoVim / VSCode / Jetbrains Suite
- **Browser**: Firefox / Brave
- **Shell**: Zsh
- **App Laucher**: Finder
- **Font**: [JetBrainsMonoNFM](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/JetBrainsMono.zip)

### ***Dependencies***

- make
- stow
- g++
- nvim 0.7.0+
- oh-my-zsh

```
brew install stow
brew install g++
```

Latest version of nvim can be downloaded from its git repo page.

Make sure to install oh-my-zsh from official site.


### ***Installation***
1. Clone this directory to your home directory.

2. Run the makefile command to symbolically link all of the configurations to this repository.

### Example

```
cd ~

cd dotfiles/

make all
```

<div align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.png"></div>
