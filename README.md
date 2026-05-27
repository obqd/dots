Steps to install: <br>
1. Install mangowc foot rofi and waybar.
  ```
  sudo pacman -S foot rofi waybar
  paru -S mangowm-git
  ```
2. Make a backup of your current configs.
  ```
  mkdir -p ~/config-bk
  cp ~/.config ~/config-bk
  ```
3. Then copy the configs over in your `.config`.
  ```
  git clone https://github.com/obqd/dots.git ~/config/
  cp -R ~/config/ ~/.config/
  ```
