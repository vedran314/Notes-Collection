## Basic Movement I.

[Vim Cheat Sheet](http://michael.peopleofhonoronly.com/vim/)

### Slow movement 

Character-wise movements with the home keys:

>h, j, k and l.

The lesson here: DON'T use the arrow keys.

### Line terminus

Beginning of line and end of line movements:

The different types of "words"

words - represent a sequence of characters in the 'iskeyword' class.
WORDs - represent a sequence of characters separated by whitespace.

Run :help word and :help WORD

### Forward word movement

We learn to move foward to the next WORD and word both to the beginning of words and the end of words.

>Commands are **w, W, e** and **E**.

### Backward word movement
We learn to move backward to the previous WORD and word both to the beginning of words and the end of words.

>Commands are **b, B, ge and gE.**

### "To the Character" movement 

The great, super great commands: 

> f, F, t, T and ;

that let you move to specific characters within a line.

***

## Basic Movement II

### Paging

Moving the page up and down by:

- full pages:
> `CTRL+f` and `CTRL-b`

- half pages:
> `CTRL+u` and `CTRL+d`

Top and Bottom of the buffer. 

Jumping to the top line of the entire buffer with `gg` and the bottom of the entire buffer with `G`.

Jump to particular line:
> <number>G

Easy regular expression searching:
> `*` and `#`

`g*` search for the word under the cursor (like *, but g* on 'rain' will find words like 'rainbow').
`g#` same as `g*` but in backward direction.

Manual regular expression searching:
> `/` and `?`

## Basic Movement III

### Moving to the beginning of functions and classes with:

> [[ , ]]

### End of Function or Class Jumping 

Forwards to the end of a function or class definition with ``][`` and backwards to the end of a function or class definition with ``[]``.

### Jump to the Matching Braces

The fantastic `%`

### Marks

- mark something with `ma`
- `'a` jump to mark a or \` a to jump to exact column of the mark












