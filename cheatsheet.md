# Cursor motion

`h`: left
`j`: down
`k`: up
`l`: right

`gj`: down (by screenline, useful when lines are wrapped)
`gk`: up (by screenline, useful when lines are wrapped)

 1. The cursor is moved using either the arrow keys or the hjkl keys.
     h (left)   j (down)       k (up)       l (right)


`gg`: Move to the first line of the file
`G`: Move to the last line of the file
{num}`G`: Move the the {num} line of the file
`g_`: Move the the last non-blank character of the line
`$`: Move to the end of the line
`^`: Move to the first non-blank character of the line
`0`: Move to the first character of the line

Adding `g` before `$`, `^` or `0` move the cursor only within the screen line.
So if you line it is wrapped, the cursor will stay on the same screen line.

`gm` Move to the middle of the display
`gM` Move to the middle of text of the line

{num}`f`{char}: Move to the {num}th occurrence of the {char} to the right 
{num}`F`{char}: Move to the {num}th occurrence of the {char} to the left
{num}`t`{char}: Move till before the {num}th occurrence of the {char} to the right
{num}`T`{char}: Move till before the {num}th occurrence of the {char} to the left

`;`: Repeat the last `f`, `F`, `t`, `T` [count] times.
`,`: Repeat the last `f`, `F`, `t`, `T` in the opposite direction [count] times.

`C-m`: Move to the line downward, on the first non blank character
`_`: Move to the line upward, on the first non blank character

# Word motion

# Visual Mode

# Autocomplete

# Useful shortcut

                 fewfewfew


Come back where I was : ctrl + shift? + o // is shift necessary ? It seems not
duplicate this line: :t.

substitute all file: :%s/old/new/g add "c" for confirmation

page up = ctrl + u
page down = ctrl + d

diff between words and WORDS is that the second includes inside the words some sepcial characeter such as "
This is a "sentence" as example.
words: split in 3 words : ", sentence, "
WORDS: 1 word only: "sentence"

change color scheme: :Telescope colorscheme

look for ide dracule color scheme for vim


autcompletion: ctrl + n : next
               ctrl + p : previous
               ctrl + y : select
               ctrl + e : Stop everything
I just have <c-s> mapped to :w<cr>

ctrl + hjkl to move focus window

delete until: dtc where c is the character


f  	N  f{char}	to the Nth occurrence of {char} to the ri
My alternative is using oo (resp. OO) to insert a new line under (resp. over) the current through this mapping: nmap oo o<Esc>k (resp. nmap OO O<Esc>j)

q: display the history of command

V do visual select of all the lines

    Move the cursor to the n in name.
    Enter visual block mode (Ctrlv).
    Press j three times (or 3j) to jump down by 3 lines; G (capital g) to jump to the last line
    Press I (capital i).
    Type in vendor_. Note: It will only update the screen in the first line - until Esc is pressed (6.), at which point all lines will be updated.
    Press Esc.
