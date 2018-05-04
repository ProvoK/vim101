# vim101
Welcome
<br>
In this workshop we will explore Vim fundamentals.
<br>
At the end of this presentation, you'll exit Vim like a pro!

---

What distinguish Vim by most of the text editors are `modes`

@ul
- Normal
- Insert
- Visual

+++

## Normal

In this mode you move into and bewteen files, run commands and much more. Exiting included.
<br>
This is the default mode and one of the most powerful ones.

> Pressing keys will not (most of time) write anything. PANIC

+++

## Insert

In this mode Vim will behave as a common text editor.

> I type. I see. Relief.

+++

## Visual

In this mode you actually make selections, like the ones you do dragging the mouse around.

> Oh gawd. I should have exited by now.

---

## Composition

Vim powerfulness and magic lives in its compositional nature.

We can distinguish between three kind of primitives:

- Motions
- Operators
- Text objects

---

## Motions

!img assets/hjkl.png


`w` moves to the start of the next `word` (first char excluded)
`W` moves to the start of the next space-separated `word`

`e` moves to the end of the current `word` (last char included)
`E` moves to the end of the current space-separated `word`

`b` and `B` moves back to the start of the previous `word`

`G` moves to the last line of file.
`gg` moves to the first line.

`0` moves to the start of the line
`$` moves to the end of the line

`{` moves to the previous paragraph
`}` moves to the next paragraph

---

## Insertion operators

All insert commands will move cursor and then change the current MODE to `insert`

`i` starts insert mode at the current position

`a` starts insert mode moving the cursor to the next char
`A` starts insert mode moving the cursor to the end of the WORD

`o` starts insert on the next line (it will create a blank line)
`O` starts insert on the previous line (it will create a blank line)

