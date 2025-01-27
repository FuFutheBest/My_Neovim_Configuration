# My_Neovim_Configuration

As we all know, Neovim is a highly customizable text editor. I have been using Neovim for a while now and I have customized it to my liking. I have added a lot of plugins and key mappings to make my workflow more efficient. I have also added a lot of custom settings to make the editor more user-friendly. In this blog post, I will share my Neovim configuration with you. I hope you find it useful.

Basically, my Neovim configuration is from a YouTuber's video [How I Setup Neovim To Make It AMAZING](https://www.youtube.com/watch?v=6pAG3BHurdM&t=4217s). He is an amazing YouTuber and I have learned a lot from his videos. I have made some changes to his configuration to suit my needs since he is a web developer and I need more features for C/C++ development.

If you don't want to struggle with the video, you can just clone my repository and use my configuration. Put it under `~/.config/nvim/` and you are good to go. (Maybe you need a little knowledge of Neovim and the plugin manager `lazy.nvim` ([lazy.nvim repo](https://github.com/folke/lazy.nvim)))

Below is the tree structure of my Neovim configuration:

```bash
├── init.lua
├── lazy-lock.json
└── lua
    └── fufu
        ├── core
        │   ├── init.lua
        │   ├── keymaps.lua
        │   └── options.lua
        ├── lazy.lua
        └── plugins
            ├── alpha.lua
            ├── autopairs.lua
            ├── auto-session.lua
            ├── bufferline.lua
            ├── colorscheme.lua
            ├── comment.lua
            ├── copilot.lua
            ├── dressing.lua
            ├── formatting.lua
            ├── gitsigns.lua
            ├── indent-blankline.lua
            ├── init.lua
            ├── linting.lua
            ├── lsp
            │   ├── lspconfig.lua
            │   └── mason.lua
            ├── lualine.lua
            ├── nvim-cmp.lua
            ├── nvim-tree.lua
            ├── substitute.lua
            ├── surround.lua
            ├── telescope.lua
            ├── todo-comment.lua
            ├── treesitter.lua
            ├── trouble.lua
            ├── vim-maximizer.lua
            └── which-key.lua
```

Discover the freedom of Neovim — I'm loving it right now! 🚀
