## Operators

+++

## Insertion operators

All insert commands will move cursor and then change the current MODE to `insert`

`i` starts insert mode at the current position

`a` starts insert mode moving the cursor to the next char
`A` starts insert mode moving the cursor to the end of the WORD

`o` starts insert on the next line (it will create a blank line)
`O` starts insert on the previous line (it will create a blank line)

+++

## Yank and paste operators

`y` copies the selection or the text object
`yy` copies the current line

`p` and `P` paste, the former after the cursor, the latter before it.

+++

## Delete operators

`x` and `X` deletes a single char
`d` deletes the selection or the text object
`dd` deletes the current line
