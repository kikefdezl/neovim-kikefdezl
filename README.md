### My custom Neovim config, based on NvChad

Installation on Ubuntu:
1. Install Neovim > 0.8 (not from apt).
2. Get JetBrainsMono font.
```bash
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/JetBrainsMono.zip
unzip -o JetBrainsMono.zip -d ~/.local/share/fonts/
rm JetBrainsMono.zip
```
3. Install `xclip` for clipboard management.
```bash
sudo apt install xclip
```
4. Install NvChad. 
```bash
sudo rm -rf ~/.config/nvim
sudo rm -rf ~/.local/share/nvim
sudo rm -rf ~/.cache/nvim
git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 
```
5. Install Custom Config.
```
sudo rm -rf ~/.config/nvim/lua/custom
git clone git@github.com:kikefdezl/neovim-kikefdezl.git ~/.config/nvim/lua/custom --depth 1
nvim
```
