
Personal neovim dotsfile, made with the aim of maximizing efficiency when programming and obtaining a minimalistic and fast configuration that allows you to be productive.
--- 
![image](https://github.com/JoseMRodriguezM/Neovim-configuration/assets/76118394/627edb12-ad3c-4cfc-b336-8f57acabe05e)
![image](https://github.com/JoseMRodriguezM/Neovim-configuration/assets/76118394/bd209e17-c2a2-44f6-92dc-8d8d98db3abe)
![image](https://github.com/JoseMRodriguezM/Neovim-configuration/assets/76118394/55bf94cc-f13d-40a8-b686-4bbf69308095)


## ⚡️ Requirements

- Neovim >= **0.8.0** (needs to be built with **LuaJIT**)
- Git >= **2.19.0** (for partial clones support)
- a [Nerd Font](https://www.nerdfonts.com/) **_(optional)_**
- a **C** compiler for `nvim-treesitter`. See [here](https://github.com/nvim-treesitter/nvim-treesitter#requirements)

## 🚀 Getting Started


</details>

<details><summary>Installation </summary>

- Make a backup of your current Neovim files:

  ```sh
  mv ~/.config/nvim ~/.config/nvim.bak
  mv ~/.local/share/nvim ~/.local/share/nvim.bak
  ```

- Clone the repositori

  ```sh
  git clone https://github.com/JoseMRodriguezM/NvimDotfiles.git ~/.config/nvim
  ```

- Remove the `.git` folder, so you can add it to your own repo later

  ```sh
  rm -rf ~/.config/nvim/.git
  ```

- Start Neovim!

  ```sh
  nvim
  ```

</details>

---

## 📂 File Structure

<pre>
C:\Users\user\AppData\Local\nvim
├── lua
│   ├── config
│   │   ├── keymaps.lua
│   │   └── options.lua
│   └── plugins
│       |── All the plugins installed and their configurations
└── init.lua
</pre>
