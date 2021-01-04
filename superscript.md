# `^superscript`


## single words

`^word`: ^word

`^^stack2`: ^^stack2

`^^^stack3`: ^^^stack3



## links

### sup is outside

`^[outside_1](/outside_of_link1)`: ^[outside_](/outside_of_link1)

`^^[outside_2](/outside_of_link2)`: ^^[outside_2](/outside_of_link2)

`^^^[outside_3](/outside_of_link3)`: ^^^[outside_3](/outside_of_link3)


### sup is inside

`[^inside_1](/inside_of_link1)`: [^inside_1](/inside_of_link1)

`[^^inside_2](/inside_of_link2)`: [^^inside_2](/inside_of_link2)

`[^^^inside_3](/inside_of_link3)`: [^^^inside_3](/inside_of_link3)



## sentences

`^(simple text with spaces, no extras!)`: ^(simple text with spaces, no extras!)

`^(this entire text is superscripted, [link](/link) too)`: ^(this entire text is superscripted, [link](/link) too)

`^(start; (some brackets) [this] {hm} ending.)`: ^(start; (some brackets) [this] {hm} ending.)

`^(start; \(escaped brackets\) \[esc this\] \{esc hm\} ending.)`: ^(start; \(escaped brackets\) \[esc this\] \{esc hm\} ending.)

`^(escaped brackets: [link2]\(/link2\) 2)`: ^(escaped brackets: [link2]\(/link2\) 2)



## html

`<sup>literally "&lt;sup&gt;"</sup>`: <sup>literally "&lt;sup&gt;"</sup>

`<sub>literally "&lt;sub&gt;"</sub>`: <sub>literally "&lt;sub&gt;"</sub>


----

currently tested:

1. [old.reddit]()
2. [new.reddit]()
3. [github]()
4. [gitlab]()
5. [codepen]()
