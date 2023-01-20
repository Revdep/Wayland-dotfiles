![hyprland+waybar-compress](https://user-images.githubusercontent.com/61702357/213812100-a8dc21c5-18bc-43c0-ad7a-abbf823e55e7.png)

 REQUIREMENTS 

<p> You can find packages to install on packages.txt (i have installed all of that). </p>

TO be able to pack/unpack dotfiles easily i used stow .
You just need to clone this repo in the home directory , then cd the repo and use stow to symlink all the dotfiles on the right place.

Example:
- If You want Hyprland:
`cd /home/$user/.dotfiles`
`stow hypr `

- If You want waybar:
 ` stow waybar `
  
  ....and so on. 
