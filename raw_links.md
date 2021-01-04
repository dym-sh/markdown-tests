# example test markdown parsing and rendering of `[links](https://links.link/link/)`


## currently tested

1. [old.reddit](https://new.reddit.com/user/dym_sh/comments/kqgb1j/markdowntests_raw_links/)
2. [new.reddit](https://old.reddit.com/user/dym_sh/comments/kqgb1j/markdowntests_raw_links/)
3. [github](https://github.com/dym-sh/markdown-tests/blob/latest/raw_links.md)
4. [gitlab](https://gitlab.com/dym-sh/markdown-tests/-/blob/latest/raw_links.md)
5. [codepen](https://codepen.io/dym-sh/pen/abmGvMP/left/?editors=1000)
6. [beaker](hyper://0cfadf84089316a605c1c9dfb7c9ae4430b1c455600d5d1f49df362a428ed089/raw_links.md) /[?](https://beakerbrowser.com)

----


#### simple link

`https://url.only.link`: https://url.only.link

`https://url.with.cloding.slash.link/`: https://url.with.cloding.slash.link/


#### folder

`https://1.link/folder_only`: https://1.link/folder_only

`https://1.link/slash_after_folder/`: https://1.link/slash_after_folder/


#### extra_underscore_

`https://2.link/folder_only_with_extra_underscore_`: https://2.link/folder_only_with_extra_underscore_

`https://2.link/slash_after_folder_with_extra_underscore_/`: https://2.link/slash_after_folder_with_extra_underscore_/


#### (round brackets)

`https://3.link/folder_only--(with+round+brackets)`: https://3.link/folder_only--(with+round+brackets)

`https://3.link/slash_after_folder--(with+round+brackets)/`: https://3.link/slash_after_folder--(with+round+brackets)/


#### [square brackets]

`https://4.link/folder_only--[with+square+brackets]`: https://4.link/folder_only--[with+square+brackets]

`https://4.link/slash_after_folder--[with+square+brackets]/`: https://4.link/slash_after_folder--[with+square+brackets]/


#### {curly brackets}

`https://5.link/folder_only--{with+curly+brackets}`: https://5.link/folder_only--{with+curly+brackets}

`https://5.link/slash_after_folder--{with+curly+brackets}/`: https://5.link/slash_after_folder--{with+curly+brackets}/


#### <angle brackets>

`https://6.link/folder_only--<with+angle+brackets>`: https://6.link/folder_only--<with+angle+brackets>

`https://6.link/slash_after_folder--<with+angle+brackets>/`: https://6.link/slash_after_folder--<with+angle+brackets>/


#### one single quote at the end'

`https://7.link/folder_only--one+single+quote+at+the+end'`: https://7.link/folder_only--one+single+quote+at+the+end'

`https://7.link/slash_after_folder--one+single+quote+at+the+end'/`: https://7.link/slash_after_folder--one+single+quote+at+the+end'/


#### 'single quoted part'

`https://8.link/folder_only--'single+quoted+part'`: https://8.link/folder_only--'single+quoted+part'

`https://8.link/slash_after_folder--'single+quoted+part'/`: https://8.link/slash_after_folder--'single+quoted+part'/


#### one double quote at the end"

`https://9.link/folder_only--one+double+quote+at+the+end"`: https://9.link/folder_only--one+double+quote+at+the+end"

`https://9.link/slash_after_folder--one+double+quote+at+the+end"/`: https://9.link/slash_after_folder--one+double+quote+at+the+end"/


#### "double quoted part"

`https://10.link/folder_only--"double+quoted+part"`: https://10.link/folder_only--"double+quoted+part"

`https://10.link/slash_after_folder--"double+quoted+part"/`: https://10.link/slash_after_folder--"double+quoted+part"/


#### question mark equals?=

`https://11.link/folder_only--question+mark+equals?=`: https://11.link/folder_only--question+mark+equals?=

`https://11.link/slash_after_folder--question+mark+equals?=/`: https://11.link/slash_after_folder--question+mark+equals?=/


### code block

here links should not be parsed at all.

    https://url.only.link
    https://url.with.cloding.slash.link/

    https://1.link/folder_only
    https://1.link/slash_after_folder/

    https://2.link/folder_only_with_extra_underscore_
    https://2.link/slash_after_folder_with_extra_underscore_/

    https://3.link/folder_only--(with+round+brackets)
    https://3.link/slash_after_folder--(with+round+brackets)/

    https://4.link/folder_only--[with+square+brackets]
    https://4.link/slash_after_folder--[with+square+brackets]/

    https://5.link/folder_only--{with+curly+brackets}
    https://5.link/slash_after_folder--{with+curly+brackets}/

    https://6.link/folder_only--<with+angle+brackets>
    https://6.link/slash_after_folder--<with+angle+brackets>/

    https://7.link/folder_only--one+single+quote+at+the+end'
    https://7.link/slash_after_folder--one+single+quote+at+the+end'/

    https://8.link/folder_only--'single+quoted+part'
    https://8.link/slash_after_folder--'single+quoted+part'/

    https://9.link/folder_only--one+double+quote+at+the+end"
    https://9.link/slash_after_folder--one+double+quote+at+the+end"/

    https://10.link/folder_only--"double+quoted+part"
    https://10.link/slash_after_folder--"double+quoted+part"/
