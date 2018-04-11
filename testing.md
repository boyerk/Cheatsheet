# Vim Cheat Sheet by Kane Boyer

#### Vim is a text editor or plugin that maximizes in effeciency using shortcuts that provide all the same functions as a mouse and is very good at using shortucts to repeat repetitive tasks. Vim also works with any language and is available on all platforms that can be used in the default terminal as well as several text editors. Vim also had very minimal memory usage.

**Insert Mode** = regular text editor, press "i" (want to write your code in this mode)

**Command/Normal Mode** = Vim shortcuts "esc" key ( want to navigate through your code in this mode)
(frequently switches between them.)

**Visual Mode** = this mode will highlight anything that the cursor moves over, and will still apply 
commands from normal mode, "v" will enter Visual Mode

## Short Cuts

```h = move cursor left```

```j = move cursor down```

```k  = move cursor up```

```w = move to the beginning of the next word```

```e = move to the end of a word```

```b = move to the beginning of a word```

```d = deletes, can be used with w, or e keys as well as numbers for example "d5w" would delete the 
next 5 words```

```dd = deletes a line, can be used with numbers 4dd would delete 4 lines```

```u = undo```

```a or A = Changes to Insert Mode after current character, or after line```

```ctr + r = redo```

```r = replaces the character underneath the cursor with any the letter typed next```

```x or X = deletes the character under the cursor```

```o or O = will add a new line, o will just add a new line, O will add a line before the previous 
line(this shortcut also changes you to Insert Mode right after use)```

```p = paste, deleting a line or a word copies it so that you can paste it```

```0 = move to the start of a line```

```$ = move to the end of a line```

```% = move to matching parentheses and or brackets```

```* = finds next current word below cursor```

```# = finds next current word above cursor```

```gg = moves cursor to the beginning of the file```

```(number)G = moves you to that line, or G by itself moves you to the bottom of your file```

```. = repeats the previous command```

```ce = deletes a word and puts you insert mode```

```Numbers = e.g number(j) will move you down that many lines "3j" will move you down 3 lines```

```f or F = finds the next letter or typed after it for example "fe" will find the next "e" if you type a number before it "5fh" this will find the fifth "h"```

```/ = opens a text box to find a word pressing "n" will jump forward to each occurance of a word "N" will jump to previous occurances of the word```