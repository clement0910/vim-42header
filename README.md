# vim-42lyonheader
a (better) vim header for 42 (lyon) projects

![fancy header image](https://imgur.com/download/GTD7kAo)

## Features
* Passes `norminette`
* Elegant trimming of long strings
* Updates filename line when changed
* Updates "Updated" line only when buffer is changed
* Works with all formats that default supports
* Binds to `F1` for easy access
* Overrides `:Stdheader` for school vim installs

DON'T FORGET TO SET YOUR `$USER` AND `$MAIL` VARIABLES.
https://www.twilio.com/blog/2017/01/how-to-set-environment-variables.html

## Usage 

### No plugin manager
Copy `42header.vim` to your `~/.vim/after/plugin/` folder. You're set!

### pathogen
```
git clone https://github.com/clement0910/vim-42lyonheader.git --recursive && mv -v vim-42lyonheader ~/.vim/bundle/
```

## Thanks to pbondoer
Original code: https://github.com/pbondoer/vim-42header
