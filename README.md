Arcadia
------
###### Arcadia version 1.0.0
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/21557226/13b91b60-cdde-11e6-96d0-7f91b4857734.png)
```VimL
colorscheme arcadia
```
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/21556686/a9e97546-cdd7-11e6-9387-f36e9b5e5858.png)


Installation
---------------
There are a few ways to install Arcadia. The first option is by using your favorite vim package manager and the second is by manual download.

###### Package Manager Option
| Manager          | Location        | Set Up                                                                    |
|------------------|-----------------|---------------------------------------------------------------------------|
| Vundle           | add to .vimrc:  | `Plugin 'alessandroyorba/arcadia'`                                         |
| NeoBundle        | add to .vimrc:  | `NeoBundle 'alessandroyorba/arcadia'`                                      |
| VimPlug          | add to .vimrc:  | `Plug 'alessandroyorba/arcadia'`                                           |
| Pathogen         | from terminal:  | `cd ~/.vim/bundle && \ git clone git://github.com/alessandroyorba/arcadia` |

###### Download Option
Download the .zip and copy `arcadia.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.

Arcadia Settings
---------------
There are several options that you can enable for Arcadia. You can activate them by adding each of the following variables to your .vimrc. Remember to place the variables before declaring `colorscheme arcadia`.

| Description                        | Set up in .vimrc                            | Screenshot                                                                |
|------------------------------------|------------------------------------------|---------------------------------------------------------------------------|
| light gray background              | `colorscheme arcadia`                    | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21556686/a9e97546-cdd7-11e6-9387-f36e9b5e5858.png)|
| medium gray background             | `let g:arcadia_Sunset = 1`               | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21556687/afe9ca0e-cdd7-11e6-9de7-c68a4cfc0c6d.png)|
| dark  gray background              | `let g:arcadia_Twilight = 1`             | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21556690/b750ef34-cdd7-11e6-9ee8-97f6cb3d1ca3.png)|
| almost black background            | `let g:arcadia_Midnight = 1`             | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21556691/bcee8032-cdd7-11e6-91d3-b1c628e085ac.png)|
| black as pitch                     | `let g:arcadia_Pitch = 1`                | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21556697/c28328e0-cdd7-11e6-9798-30d23087439a.png)|

Moar Screenshots
----------------
[Screenshots](https://github.com/AlessandroYorba/Arcadia/issues/1)

The screenshots of Arcadia were made and tested using a default Vi IMproved 7.4 in [iTerm 3](https://www.iterm2.com) and the Vi IMproved 7.4 in the GUI MacVim app. Extended syntax for JavaScript provided by Jose Elera Campana's Plug-in [vim-javascript-syntax](https://github.com/jelera/vim-javascript-syntax). Enjoy!!

Related 
-------
Feedback, issues or suggestions?. Open an Issue [Arcadia Issues](https://github.com/AlessandroYorba/Arcadia/issues)! Also, if you like Arcadia you might want to check out some of the other Vim themes that I'm working on:  

Alduin  
[![alduinPalette](https://cloud.githubusercontent.com/assets/11221489/21478385/c632e44c-caff-11e6-9b0e-f5eb2a146dbb.png)](https://github.com/AlessandroYorba/Alduin) 

Despacio  
[![despacioPalette](https://cloud.githubusercontent.com/assets/11221489/21478144/5ac3afe0-cafd-11e6-90b2-e19411e3e0a3.png)](https://github.com/AlessandroYorba/Despacio) 

Sierra  
[![sierraPalette](https://cloud.githubusercontent.com/assets/11221489/21478384/c2959122-caff-11e6-9728-6da758989804.png)](https://github.com/AlessandroYorba/Sierra)
