# svg: currentColor

## currently tested

1. [github](https://github.com/dym-sh/markdown-tests/blob/latest/current_color.md)
2. [gitlab](https://gitlab.com/dym-sh/markdown-tests/-/blob/latest/current_color.md)
3. [codepen](https://codepen.io/dym-sh/pen/zYZPjWE/left/?editors=1100)


## just testing
![](current_color.svg)


## inside a h2-tag
## ![](current_color.svg)


## inside a p-tag, as img
<p>
  some p-tag text before
  <img src='current_color.svg'>
  some p-tag text after
</p>


## inline-svg
<p>
  some p-tag text before
  <svg
    xmlns='http://www.w3.org/2000/svg'
    viewBox='0 0 100 15'
    >
    <rect
      width='100'
      height='7'
      fill='currentColor'
      />
    <rect
      width='100'
      height='7'
      y='8'
      fill='currentColor'
      />
    <text
      y='1em'
      font-size='10'
      fill='currentColor'
      style='filter:invert()'
      >
      testing
    </text>
  </svg>
  some p-tag text after
</p>
