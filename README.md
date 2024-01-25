# mydotfiles
rice

## Details
For firefox, you need to get Wavefox. Try following the instructions on their github, https://github.com/QNetITQ/WaveFox, but just copy my chrome folder instead of downloading their release so that it will be the same, but you still need to update several about:config options (I used tabs option 12). The transparency offered by Wavefox didn't work out of the box for me, so my userChrome.css is slightly different than the one that came with wavefox (and I had to set opacity of firefox to 0.999... in hyprland.conf to get it to work). Most everything else should work out of the box, except for things like hyprpaper that reference images stored at random in my computer, which you'll have to change. If you copy my config, I recommend doing it one thing at a time and making adjustments where necessary. For waybar, to make changing the color easy, I have a customcolors.css file that makes it easier to change the color of the whole thing. I tried that with wofi, but it didn't work so you'll need to change the colors manually (vim :%s/#<current-color>/#<new-color>/g should suit you in style.css).

I launch apps using keybinds (e.g., $mod+a for Spotify), so go into hyprland.conf and change those to ones that suit you.
Hyprpaper displays my background. Just change the path to wherever your wallpaper is.

Wallpaper: https://wall.alphacoders.com/big.php?i=774883

Let me know if you need any help! (or read the docs like a sane person)
