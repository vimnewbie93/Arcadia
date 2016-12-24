Arcadia
------
###### Arcadia version 1.0.0
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/21464468/aa5a2740-c932-11e6-8a71-3db340179e7a.png)
```VimL
colorscheme arcadia
```


Installation
---------------
There are a few ways to install Arcadia. The first option is by using your favorite vim package manager and the second is by manual download.

###### Package Manager Option
| Manager          |                 |                                                                           |
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

| Description                        | Add to .vimrc                            | Screenshot                                                                |
|------------------------------------|------------------------------------------|---------------------------------------------------------------------------|
| light gray background              | `colorscheme arcadia`                    | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21464604/b46c7478-c936-11e6-94c7-0c0d3037d53f.png)|
| medium gray background             | `let g:arcadia_Sunset = 1`               | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21464614/12afa23a-c937-11e6-8b85-6f5053fbe515.png)|
| dark  gray background              | `let g:arcadia_Twilight = 1`             | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21464619/3c5d4362-c937-11e6-8f8d-61af7fde79ee.png)|
| almost black background            | `let g:arcadia_Midnight = 1`             | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21464630/9b4ab404-c937-11e6-9cb3-afc4a3f8cefa.png)|
| black as pitch                     | `let g:arcadia_Pitch = 1`                | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/21464634/dea0ae02-c937-11e6-92b3-acfcf51bd235.png)|

Moar Screenshots
----------------
[Screenshots](https://github.com/AlessandroYorba/Arcadia/issues/1)

The screenshots of Arcadia were made and tested using a default Vi IMproved 7.4 in [iTerm 3](https://www.iterm2.com) and the Vi IMproved 7.4 in the GUI MacVim app. Extended syntax for JavaScript provided by Jose Elera Campana's Plug-in [vim-javascript-syntax](https://github.com/jelera/vim-javascript-syntax). Enjoy!!

Related 
-------
Feedback, issues or suggestions?. Open an Issue [Arcadia Issues](https://github.com/AlessandroYorba/Arcadia/issues)! Also, if you like Arcadia you might want to check out some of the other Vim themes that I'm working on:
* ![alduinPalette](https://cloud.githubusercontent.com/assets/11221489/21464544/105be1bc-c935-11e6-88c9-763d83a919ce.png) [Alduin](https://github.com/AlessandroYorba/Alduin)
* ![despacioPalette](https://cloud.githubusercontent.com/assets/11221489/21464535/ac047602-c934-11e6-92ef-d5cbfb7d1583.png) [Despacio](https://github.com/AlessandroYorba/Despacio)
* ![sierraPalette](https://cloud.githubusercontent.com/assets/11221489/21464553/68817d84-c935-11e6-9419-9e2537696e2d.png) [Sierra](https://github.com/AlessandroYorba/Sierra)
