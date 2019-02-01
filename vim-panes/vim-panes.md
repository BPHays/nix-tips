# Editing Multiple files at once with vim panes

## Opening a New Vim Pane

`:split <file>`: Splits the window horizontally
`:vsplit <file>`: Splits the window Vertically
`:sp <file>` and `:vsp <file>`: Are shorter versions of the above for the impatient

## Navigating between panes

`<ctrl>w <direction>` where `<direction>` is one of `hjkl` or the arrow keys. I highly recommend getting used to navigating vim with your home row keys, but that's up to you.

## Why Use Panes

The most obsious reason is when working with multiple files in a project.

Another time it can be very useful is when working with different parts of the same file. If you don't specify a `<file>` then you just get another pane in the same file. If you want to go and look at some code elsewhere you can split the pane and navigate to the interesting portion without moving the other pane. I use it this way a lot.

## My Keybindings

```
nnoremap <C-j> <C-W>j
nnoremap <C-k> <C-W>k
nnoremap <C-h> <C-W>h
nnoremap <C-l> <C-W>l
```

I bind `<ctrl><direction>` to change panes, which saves me having to do have two distint keypresses to change panes. It sounds minor, but when you do it a few hundred times a day it's nice.
