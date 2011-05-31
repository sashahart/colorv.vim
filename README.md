INTRO:
    
NEW!(1.2.0)  Color name (W3C Standard) Supported,like OrangeRed lime cadetblue
**ColorV** or **ColorV.vim** is a Color Viewer and Color Picker of Vim.

Open a ColorV window.
    <leader>cv

Open a ColorV window by word under cursor.
    #ff9744 or rgb(33,44,155) or orangered
    put cursor on above words 
    <leader>cw

Change the word under cursor with chosing color after quit the ColorV window.
    <leader>cg

Copy the color in the ColorV window
    yy

If you have '+python' compiled and pygtk2.0.
You could use a GTK eyedropper to get colors on screen.
    <leader>cd

There are many configs and commands and variable to define. 
See detail in help docs.

Have a look at it. http://flic.kr/p/9LuPxG
or http://i55.tinypic.com/330ryhl.jpg

If useful for you, please rate it
http://www.vim.org/scripts/script.php?script_id=3597

If you have any advice ,patches or bug reports.
Submit it at github: https://github.com/rykka/colorv>

INSTALL:
    
Using vim.org:
http://www.vim.org/scripts/script.php?script_id=3597
Download the latest version of tar.gz file, extract it.
And put plugin files into your VIMFILE folder.
("~/.vim" for linux. "$HOME/vimfiles" for windows)

Then use help tag to generate tags.

    :helptags VIMFILE/doc

Using git:
cd to your vimfile path, then use git clone.

    git clone git://github.com/rykka/ColorV.git


Using Vundle:
First, install the script Vundle.vim
then put this line in your vimrc

    Bundle 'rykka/colorv'

and use this to install it.

    :BundleInstall

 
