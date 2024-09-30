# Explorer Mode Commands

    % = Make File
    d = Make dir

# Normal Mode Commands

    d<motion> = delete
    dd = delete line
    
    y = yank

    cw = change word (from cursor to end of word)
    ciw = change inner word (full word regardless of cursor)

    <Spc>pv = Exit
    <Spc>pf = Search files
    <Spc>ps = Search git files
    ctrl+c = Exit insert mode

## Cursor Movement Commands

    k = up one line
    j = down one line
    h = left one character
    l = right one character

    w|W = jumps forward to start of word (caps to ignore punc)
    e|E = jumps to end of word (caps to ignore punc)
    b|B = jumps backward to the start of previous word (caps to ignore punc)
    ge|gE = jumps backward to the end of a word (same caps behavior)

    f<character> = move cursor to next occurance of character

    A = enter insert mode at the end of your current line
    C = del everything to end of line and enter insert mode

    gg = top of file
    G = end of file
    
    ctrl+w+h|j|k|l = Move windows (Useful for things like Undotree)

## Undotree Commands (undotree.lua)

    <Spc>u = Open Undotree

## Harpoon Commands (harpoon.lua)
    
    <Spc>a = Mark file
    
    ctrl+e = toggle menu

    ctrl+h = Jump to file (1)
    ctrl+t = Jump to file (2)
    ctrl+n = Jump to file (3)
    ctrl+s = Jump to file (4)

## LSP Commands (customized, lsp.lua)

    ctrl+p = Select previous item
    ctrl+n = Select next item
    ctrl+y = confirm
    ctrl+Spc = complete

### Vim LSP buffer fallbacks

    These are fallbacks if you don't have an LSP installed for this lang and want vim to make a best effort:
    gd = Go to definition
    K = Hover (?)
    <Spc>vws = Workspace symbol (?)
    <Spc>vd = Open float (?)
    [d = go to next
    ]d = go to previous
    <Spc>vca = Code action (?)
    <Spc>vrr = References (?)
    <Spc>vrn = Rename
    
    ctrl+h = Signature help (in Insert Mode)


# Visual Mode Commands

    v = visual mode
    V = visual SELECT mode
    ^v = visual BLOCK mode

    = = auto indent code

# LSP Commands (customized)

    <C-p> = select prev item
    <C-n> = select next item
    <C-y> = confirm
    <C-Space> = complete


    gd = Go to Declaration
    K = Hover (?)
    <leader>vws = Workspace symbol (?)
    <leader>vd = Open float (?)
    [d = Go to next
    ]d = go to prev
    <leader>vca = code action (?)
    <leader>vrr = references (?)
    <leader>vrn = rename
	<C-h> = signature help (?) (while in Insert mode)


