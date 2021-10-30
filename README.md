# bookmenu
TUI for LibGen using the InterPlanetary File System.  
Inspired by: https://odysee.com/@metalx1000:c/retro-style-most-wanted

![preview](preview.png)

## requirements
- viu (https://github.com/atanunq/viu)
- wget

## installation
Arch based distros: the ![bookmenu-git]("https://aur.archlinux.org/cgit/aur.git/tree/PKGBUILD?h=bookmenu-git")  
Edit the script options as needed (ebook format, upstream links, output directory and TUI size).

## usage
Launch the script with: ```bookmenu {query}```   
n -> go to the next book  
p -> go to the previous book  
d -> download the book  
q -> quit the tui  

## quirks   
- Many ISPs have started blacklisting the domains used to scrape the books information.  
Please update your /etc/resolv.conf to use a different DNS or even better, host one by yourself.
