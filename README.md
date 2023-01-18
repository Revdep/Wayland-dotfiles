![2023-01-17-18:25:11_Screenshot](https://user-images.githubusercontent.com/61702357/213056300-7f4f028c-330a-4d98-a0c9-9516bda09df1.png)


<h1> REQUIREMENTS <h1>

<p> You can find packages to install on lista-pacchetti (i have all of that). </p>

TO be able to pack/unpack dotfiles easily i used stow .
You just need to clone this repo in the home directory , then cd the repo and use stow to symlink all the dotfiles on the right place.

Example:
- If You want Hyprland:
cd /home/$user/.dotfiles
stow hypr 

- If You want waybar:
  stow waybar 
  
  ....and so on. 
