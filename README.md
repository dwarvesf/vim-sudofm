## vim-sudofm

vim-sudofm is a plugin for Vim that provides simple [sudo.fm](https://sudo.fm) integration. sudo.fm is a service that aggregate and provide music playlist for programmers.

## Usage

- `:SudoStart` - will start the player with coding mood
- `:SudoStart <mood>` - will start the with chosen mood
- `:SudoStop` - will pause the player
- `:SudoShuffle` - will switch to another playlist
- `:SudoApiKey` - change the api key saved in your ~/.sudofm.cfg
- `:SudoDebugEnable` - enable debug mode (may slow down Vim so disable when finished debugging)
- `:SudoDebugDisable` - disable debug mode

## Installation

1. Install vim plugin
2. Enter your `APIKey`, then press `Enter`
3. Use Vim and start the music, your stats will be displayed on your sudo.fm dashboard

### Via Plugin Manager (Recommended)

#### [Vim-Plug](https://github.com/junegunn/vim-plug)

1. Add `Plug 'dwarvesf/vim-sudofm'` to your vimrc file.
2. Reload your vimrc or restart
3. Run `:PlugInstall`

#### [Vundle](https://github.com/VundleVim/Vundle.vim) or similar

1. Add `Plugin 'dwarvesf/vim-sudofm'` to your vimrc file.
2. Reload your vimrc or restart
3. Run `:BundleInstall`

#### [NeoBundle](https://github.com/Shougo/neobundle.vim)

1. Add `NeoBundle 'dwarvesf/vim-sudofm'` to your vimrc file.
2. Reload your vimrc or restart
3. Run `:NeoUpdate`

#### [Pathogen](https://github.com/tpope/vim-pathogen)

```sh
cd ~/.vim/bundle
git clone https://github.com/dwarvesf/vim-sudofm.git
```

### Manual Installation

#### Unix

(For Neovim, change `~/.vim/` to `~/.config/nvim/`.)

```sh
curl -fLo ~/.vim/plugin/sudofm.vim --create-dirs \
  https://raw.githubusercontent.com/dwarvesf/vim-sudofm/master/plugin/sudofm.vim
```

#### Windows (PowerShell)

```powershell
md ~\vimfiles\plugin
$pluguri = 'https://raw.githubusercontent.com/dwarvesf/vim-sudofm/master/plugin/sudofm.vim'
(New-Object Net.WebClient).DownloadFile($pluguri, $ExecutionContext.SessionState.Path.GetUnresolvedProviderPathFromPSPath("~\vimfiles\plugin\sudofm.vim"))
```

## Screenshot

## License

MIT @ [Dwarves Foundation](https://dwarves.foundation)
