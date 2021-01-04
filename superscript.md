# example test markdown parsing and rendering of `^superscript`


## currently tested

1. [new.reddit](https://new.reddit.com/user/dym_sh/comments/kq9n3n/this_is_a_superscripttest_post/)
2. [old.reddit](https://old.reddit.com/user/dym_sh/comments/kq9n3n/this_is_a_superscripttest_post/)
3. [github](https://github.com/dym-sh/markdown-tests/blob/latest/superscript.md)
4. [gitlab](https://gitlab.com/dym-sh/markdown-tests/-/blob/latest/superscript.md)
5. [codepen](https://codepen.io/dym-sh/pen/rNMvOYJ/left/?editors=1000)
6. [beaker](hyper://0cfadf84089316a605c1c9dfb7c9ae4430b1c455600d5d1f49df362a428ed089/superscript.md) /[?](https://beakerbrowser.com)

----


## single words

`^word`: ^word

`^^stack2`: ^^stack2

`^^^stack3`: ^^^stack3



## links

### sup is outside

`^[outside_1](/outside_of_link1)`: ^[outside_1](/outside_of_link1)

`^^[outside_2](/outside_of_link2)`: ^^[outside_2](/outside_of_link2)

`^^^[outside_3](/outside_of_link3)`: ^^^[outside_3](/outside_of_link3)


### sup is inside

`[^inside_1](/inside_of_link1)`: [^inside_1](/inside_of_link1)

`[^^inside_2](/inside_of_link2)`: [^^inside_2](/inside_of_link2)

`[^^^inside_3](/inside_of_link3)`: [^^^inside_3](/inside_of_link3)



## sentences

`^(simple text with spaces, no extras!)`: ^(simple text with spaces, no extras!)

`^(start; (some brackets) ending.)`: ^(start; (some brackets) ending.)

`^(start; [this] ending.)`: ^(start; [this] ending.)

`^(start; {hm} ending.)`: ^(start; {hm} ending.)

`^(start; \(escaped brackets\) \[esc this\] \{esc hm\} ending.)`: ^(start; \(escaped brackets\) \[esc this\] \{esc hm\} ending.)


### sentences with links

`^(this entire text is superscripted, [link](/link) too)`: ^(this entire text is superscripted, [link](/link) too)

`^(escaped link-brackets: [link2]\(/link2\) 2)`: ^(escaped link-brackets: [link2]\(/link2\) 2)


### nested superscript

`^(super-nesting ^(level 2 ^(level 3) back-2) back-1)`: ^(super-nesting ^(level 2 ^(level 3) back-2) back-1)



## html

`<sup>literally "&lt;sup&gt;"</sup>`: <sup>literally "&lt;sup&gt;"</sup>

`<sub>literally "&lt;sub&gt;"</sub>`: <sub>literally "&lt;sub&gt;"</sub>