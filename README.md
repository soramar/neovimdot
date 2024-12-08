## Setup
1. neovim install
```bash
brew install neovim
```

2. cd
```bash
cd ~/.config/
```

3. clone
```bash
git clone https://github.com/fs0414/neovimdot.git
```

4. dir rename
```bash
mv neovimdot nvim
```

5. dependence install
```bash
brew install lazygit fzf
```

6. packer install
```bash
git clone https://github.com/wbthomason/packer.nvim \
  ~/.local/share/nvim/site/pack/packer/opt/packer.nvim
```

7. nvim
```bash
nvim lua/plugins.lua
```

8. PackerSync
```vim
:PackerInstall
```

Note
- fzfが行けなかった
  - zsh定義が足りない？
