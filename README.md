# bookmenu
TUI for LibGen using the InterPlanetary File System.  
Inspired by: https://odysee.com/@metalx1000:c/retro-style-most-wanted

![preview](preview.png)

## requirements
- chafa
- wget

## installation
For arch based distros the bookmenu-git package is available in the AUR.  
Edit the script options as needed (ebook format, upstream links, output dir, etc..).  
To chose the right proxy go to https://en.z-lib.org/ copy the link beneath "Books", once loaded, then put in the URL1 variable.

## usage
Launch the script with: ```bookmenu {query}```   
n -> go to the next book  
p -> go to the previous book  
d -> download the book  
q -> quit the tui  

## quirks   
- Many ISPs have started blacklisting the domains used to scrape the books information.  
Please update your /etc/resolv.conf to use a different DNS or even better, host one by yourself.
- Regarding the annoying wget "SSL_INIT" even when in quiet mode,  
it will be fixed in the next wget release: https://lists.gnu.org/archive/html/bug-wget/2021-09/msg00010.html
