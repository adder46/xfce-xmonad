# xfce-xmonad

**Step 1**:

Install everything:

```sh
sudo apt install ghc xmonad xmobar
```

**Step 2**:

Copy `xmonad/xmonad.hs` and `.xmobarrc` to `$HOME`:

```sh
cp -r xmonad ~
cp .xmobarrc ~
```

**Step 3**:

```sh
echo 'xmobar &' > ~/.xsessionrc
```

**Step 4**:

Set default WM:

https://askubuntu.com/questions/143376/how-to-change-the-xfce4-default-window-manager

Enjoy!
