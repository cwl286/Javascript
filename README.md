# kakuyomu-crawler


Python

This is a script to create epud and mobi by fetching novels from [kakuyomu](https://kakuyomu.jp/explore).

[epub example] (https://drive.google.com/drive/folders/1fKXPQ9-_Ag04EQQo0SFiHUbkqyHS0-Iw)
[mobi example] (https://drive.google.com/drive/folders/1bU3aygB0_vMWCzvsyJLs_p5cPy8gkJJa?usp=sharing)

INPUT = {basename} of url (https://kakuyomu.jp/works/16816452219449457673)[https://kakuyomu.jp/works/16816452219449457673)[]
e.g. INPUT = 16816452219449457673

#### Note
* It mounts Google drive
    * create two folder for each novel 
    * e.g. a orignal html folder "16816452219449457673" and a parsed html folder "16816452219449457673_org"
    * Copy parsed htmls to Colab drive
* It will download all episodes in Colab drive.
* It will parse all into html and generate epub and mobi.
* Copy htmls and parsed htmls to your Google drive


#### Folder structure
Google Drive <br/>
├──syosetu <br/> 
&emsp;└──epub <br/>
&emsp;└──mobi <br/>
&emsp;└──16816452219449457673 <br/>
&emsp;└──16816452219449457673_org <br/>
&emsp;└──... <br/>
