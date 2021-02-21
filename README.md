# How to Install in Node.js

With npm

> npm install insta-style

### To Directly Import from Github Use a Link Like This

`https://raw.githack.com/GoodStuffing123/insta-styles/master/default.css`

# How to Use

To use in an HTML file, simply import it in the header using a `link` tag.

`<link rel="stylesheet" href="insta-style/default.css" />`

To import in a JavaScript file, import it using `import` or `require`.

`import "insta-style/default.css";`

or

`require("insta-style/default.css");`

## List of Different Theme Files

This package comes with multiple different style themes. Just set the name of the CSS file to the name of the theme within your import with `.css` at the end to use it.

#### Themes

- default
- professional
- spring
- summer
- autumn
- winter

> More themes coming in the future!

## Extras

Here are some extra things you can do to customize your styles a little more.

> Note that these are not required to make the package work! This is mostly a plug and play sort of thing that you shouldn't have to do much if anything to get your web page looking good!

#### Color Classes (these will change based on the theme you pick)

Background color

- c1
- c2
- c3
- c4
- c5

Text color

- c1-text
- c2-text
- c3-text
- c4-text
- c5-text

#### Placement Classes

- center _align text center_

- left _float items left_

- right _float items right_

- right _float items right_

#### Padding Classes

- p0 _padding 0_

- p1 _padding 1rem_

- p2 _padding 2rem_

- p3 _padding 3rem_

- p4 _padding 4rem_

- p5 _padding 5rem_

- p6 _padding 6rem_

#### Margin Classes

- All Edges

  - m0 _margin 0_

  - m1 _margin 1rem_

  - m2 _margin 2rem_

  - m3 _margin 3rem_

  - m4 _margin 4rem_

  - m5 _margin 5rem_

  - m6 _margin 6rem_

- Bottom

  - mb0 _margin bottom 0_

  - mb1 _margin bottom 1rem_

  - mb2 _margin bottom 2rem_

  - mb3 _margin bottom 3rem_

  - mb4 _margin bottom 4rem_

  - mb5 _margin bottom 5rem_

  - mb6 _margin bottom 6rem_

- Top

  - mt0 _margin top 0_

  - mt1 _margin top 1rem_

  - mt2 _margin top 2rem_

  - mt3 _margin top 3rem_

  - mt4 _margin top 4rem_

  - mt5 _margin top 5rem_

  - mt6 _margin top 6rem_

- Left

  - ml0 _margin left 0_

  - ml1 _margin left 1rem_

  - ml2 _margin left 2rem_

  - ml3 _margin left 3rem_

  - ml4 _margin left 4rem_

  - ml5 _margin left 5rem_

  - ml6 _margin left 6rem_

- Right

  - mr0 _margin right 0_

  - mr1 _margin right 1rem_

  - mr2 _margin right 2rem_

  - mr3 _margin right 3rem_

  - mr4 _margin right 4rem_

  - mr5 _margin right 5rem_

  - mr6 _margin right 6rem_

# More Info

To make a navbar use this format

```
<nav>
  <ul>
    <li>Stuff Inside</li>
  </ul>
</nav>
```

To make a footer use this format (You can have as many `ul` as you want)

```
<footer>
  <div>
    <ul>
      <li>Stuff Inside</li>
    </ul>

    <ul>
      <li>More Stuff Inside</li>
    </ul>
  </div>

  <span>&copy; Your Copyright 2021<span>
</footer>
```

**That's just about everything, have fun!**
