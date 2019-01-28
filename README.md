# Vim_Tips

## Modes

### Command mode

- You press `:` key to enter command mode
- You can make commands
- You may use sentences but also character or combination of characters

### Normal mode

- You press `Esc` key to enter normal mode
- You may navigate, edit simple things...
- You may do simple commands

### Insert mode

- You may press `i` key from normal mode to enter Insert mode
- not only `i`, but also `i`, `s`, `S`, `a`, `A`, `o`, `O`, `C` applies (in different manner).
- You will edit texts
- But you cannot do any commands so use `Esc` key to go back to normal mode

### Visual mode

- You can select a lot of texts in this mode

### Basics

- Command can be sentence, character or combination of characters.
- Combination of characters can be "do this and do that", or "do it to this"
- You may also add number before character in order to repeat the command or go to certain line
- LOWER CASE AND UPPER CASE OF A CHARACTER ARE DIFFERENT

## Commands

### Command mode

- `:q`   quit
- `:q!`  quit without saving
- `:w`    write (save)
- `:wq`  write and quit
- `:(num)`  go to line (num)
- `:set number`  view line number
- `:%s/(target)/(replacement)/(g)(c)` replace text. g is greedy, without asking. c is to ask delete? y/s to each words.

### Normal mode

- `u`       undo
- `ctrl r`  redo
- `w`       go to beginning character of next word
- `e`       go to last character of next word
- `b`       go to first character of the preceding word
- `$`       go to end of the line
- `gg`      go to head of the doc
- `G`       go to end of the doc
- `0`       go to first char of the line
- `p`       paste
- `x`       delete character
- `dd`      delete line
- `dw`      delete word
- `ce`      delete to the end of the word, and go to insert mode
- `c$`      delete to the end of the line, and go to insert mode
- `Esc Esc` escape from insert mode quickly
- `ZZ`      quit
- `/`       search string

### Bonus: while searching

- `n`       go next
- `N`       go backword

