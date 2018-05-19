## Operators

+++

## Insertion operators

All the following commands will both:

@ol

- move cursor
- change the current MODE to @color[#f49e42](insert)

@olend

+++
@color[white](@size[2.0em](i and I))
@ul

- @color[#f49e42](i) starts insert mode at the current position
- @color[#f49e42](I) starts insert mode at line's start

@ulend

+++
@color[white](@size[2.0em](a and A))
@ul

- @color[#f49e42](a) starts insert mode at next char
- @color[#f49e42](A) starts insert mode at line's end

@ulend

+++
@color[white](@size[2.0em](o and O))
@ul

- @color[#f49e42](o) starts insert mode at the next line
- @color[#f49e42](O) starts insert mode at the previous line
- both will create a blank line!

@ulend

+++

## Yank and paste operators

This operators are the common CTRL+C and CTRL+V @size[0.4em](Stackoverflow programming style)

@ul

- @color[#f49e42](y) copies the selection or the text object
- @color[#f49e42](yy) copies the current line
- @color[#f49e42](p) and @color[#f49e42](P) paste, the former after the cursor, the latter before it.

@ulend

+++

## Delete operators

@ul

- @color[#f49e42](x) and @color[#f49e42](X) delete a single char
- @color[#f49e42](d) deletes the selection or the text object
- @color[#f49e42](dd) deletes the current line

@ulend

+++

## Change operator

- @color[#f49e42](c) for change. It's like @color[#f49e42](delete) + @color[#f49e42](i)
- It's very useful, as we'll see when introducing text objects

+++

## HINT

### @color[#f49e42](u) will @color[#f49e42](undo) last change
<br>
@size[0.3em](such unexpected)

+++

## Let's try!
<br>
> vim @color[#f49e42](02_operators.txt)
<br>
> spoiler: exit with @color[#f49e42](:q!)
