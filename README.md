# bookmenu
Terminal user interface ebooks browser and downloader for LibGen using the InterPlanetary File System.  
Inspired by: https://lbry.tv/@metalx1000:c/retro-style-most-wanted:2

![preview](preview.png)

## requirements
- chafa
- wget

## installation
Arch Linux: ```yay -S bookmenu-git || ${your_aur_helper} -S bookmenu-git```

## usage
Edit the script options as needed (ebook format, upstream links, output directory).  
Launch the script with: ```bookmenu {query}```.
Once started:
n -> go to the next book
p -> go to the previous book
d -> download the book
q -> quit the tui
