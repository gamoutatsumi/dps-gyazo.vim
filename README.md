# dps-gyazo.vim

Vim/Neovim plugin for Gyazo powered by
[denops.vim](https://github.com/vim-denops/denops.vim)

Respect for [skanehira/gyazo.vim](https://github.com/skanehira/gyazo.vim).

## Install

If you already installed [skanehira/gyazo.vim](https://github.com/skanehira/gyazo.vim), this plugin will conflict.

### dein.vim

```vim
call dein#add('vim-denops/denops.vim')
call dein#add('gamoutatsumi/dps-gyazo.vim')
```

## Requirements

- [Deno](https://deno.land)
- [denops.vim](https://github.com/vim-denops/denops.vim)
- xclip (Linux only)

## Usage

```vim
" upload specified file
:GyazoUpload [file]
" uplaod from clipboard
:GyazoUpload
```

## License

[MIT](./LICENSE)
