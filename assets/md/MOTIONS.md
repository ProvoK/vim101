# Motions

![hjkl-movement](assets/images/hjkl.png)

+++

- @color[#f49e42](w) moves to the start of the next @color[#f49e42](word) (first char excluded)
- @color[#f49e42](W) moves to the start of the next @color[#f49e42](WORD)

+++

@color[white](@size[2.0em](word vs WORD?))

- A @color[#f49e42](WORD) is delimited by whitespace
- A @color[#f49e42](word) is delimited by non-keyword chars (configurable)

```
these are normal words. This_is too a normal word.

this-is-a-WORD and-this-is-another-WORD
```
@[1](normal words)
@[3](blank separated words aka WORDS)
+++

@color[#f49e42](e) and @color[#f49e42](E) move to the end of the current @color[#f49e42](word) or @color[#f49e42](WORD) (last char included)

+++

@color[#f49e42](b) and @color[#f49e42](B) move back to the start of the previous @color[#f49e42](word) or @color[#f49e42](WORD)

+++

- @color[#f49e42](G) moves to the last line
- @color[#f49e42](gg) moves to the first line

+++

- @color[#f49e42](0) moves to the start of the line
- @color[#f49e42]($) moves to the end of the line

+++

- @color[#f49e42]({) moves to the previous paragraph
- @color[#f49e42](}) moves to the next paragraph

+++

## Let's try!
<br>
> vim @color[#f49e42](01_motion.txt)
<br>
> spoiler: exit with @color[#f49e42](:q!)
