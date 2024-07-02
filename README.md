<h1 align="center">Gruvbox Sayori</h1>
<h4 align="center">Config files for i3wm</h4>
<p align="center">
<img src="https://github.com/monte0x00/dotfiles-i3wm/blob/main/xd.png">
</p>
<p align="center">
<a href="#installation">Installation</a><br>
<a href="#dependencies">Dependencies & Fonts</a><br>
<a href="#shortcuts">Shortcuts</a><br>
</p>

<p align="center">
<h2>preview i3wm, picom, alacritty</h2>
  <img src="screenshot1.gif">
  <img src="screenshot3.gif">
<h2>preview rofi (dmenu & rofi-power-menu)</h2>
  <img src="screenshot2.gif">
</p>

<a name="installation"></a>
<h1 align="center">Installation</h1>

- Clone the repo

  ```
  git clone https://github.com/monte0x00/dotfiles-i3wm.git
  ```

- Open the file and copy the configurations folders to **~/.config** folder

  ```
  cd dotfiles-i3wm
  ```

  ```
  sudo cp -r alacritty i3 polybar rofi ~/.config
  ```

- Install Fonts

  ```
  cd dotfiles-i3wm
  ```

  ```
  cd fonts
  ```

  ```
  sudo cp -r CascadiaCode.ttf CascadiaCode.woff2 CascadiaCodeNF-Regular.oft CascadiaCodeNF-Regular.ttf CascadiaCodeNF-Regular.woff2 SymbolsNerdFontMono-Regular.ttf SymbolsNerdFont-Regular.ttf /usr/share/fonts
  ```

- Install Lain Wallpaper (we may have to create a backgrounds folder)

  ```
  cd dotfiles-i3wm-nord-lain
  ```

  ```
  sudo mkdir /usr/share/backgrounds
  ```

  ```
  sudo cp -r lain.jpg /usr/share/backgrounds
  ```

<a name="dependencies"></a>
<h1 align="center">Dependencies & Fonts</h1>
<h4>Dependencies can be Easily Installed from Terminal</h4>

| ***Dependencies***                   |
| -----                                |
| alacritty                            |
| xrandr                               |
| thunar                               |
| feh                                  |
| rofi                                 |
| polybar                              |
| xclip                                |
| maim                                 |

| ***Fonts***                          |
| -----                                |
| Cascadia Code                        |
| Symbols Nerd Font                    |

<p>https://github.com/microsoft/cascadia-code</p>
<p>https://www.mediafire.com/file/oho6hw6asmn3vwz/SymbolsNerdFont-Regular.ttf/file</p>
<p>https://www.mediafire.com/file/dcmhg8lac1fxdzr/SymbolsNerdFontMono-Regular.ttf/file</p>

<a name="shortcuts"></a>
<h2>Shortcuts</h2>

| ***Key***                            | ***Action***               |
| -----                                | -----                      |
| ***Software***                       | ***Action***               |
| Super + t                            | alacritty                  |
| Super + a                            | rofi -show drun            |
| Super + Shift + q                    | rofi -show power-menu      |
| Super + e                            | thunar                     |
| Print                                | maim, xclip                |
| -----                                | -----                      |
| ***i3wm***                           | ***Action***               |
| Super + q                            | kill focused window        |
| Super + Left, Down, Up, Right        | toggle window focus        |
| Super + Shift + Left,Down,Up,Right   | move focused window        |
| Super + Space                        | toggle floating/tiling     |
| Super + f                            | toggle fullscreen          |
| Super + 1,2,3,4,5,6,7,8,9,0          | focus desktop 1-9          |
| Super + Shift + 1,2,3,4,5,6,7,8,9,0  | move window to desktop 1-9 |
| Super + Shift + r                    | restart i3wm               |
