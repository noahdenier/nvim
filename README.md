# Explorer Mode Commands

    % = Make File
    d = Make dir

# Normal Mode Commands

    d<motion> = delete
    dd = delete line
    _pv = Exit
    ctrl+c = Exit insert mode

## Cursor Movement Commands

    k = up one line
    j = down one line
    h = left one character
    l = right one character

    y = yank
    
    cw = Change word
    ciw = Change inner word

    w|W = jumps forward to start of word (caps to ignore punc)
    e|E = jumps to end of word (caps to ignore punc)
    b|B = jumps backward to the start of previous word (caps to ignore punc)
    ge|gE = jumps backward to the end of a word (same caps behavior)

    f<character> = move cursor to next occurance of character

    A = enter insert mode at the end of your current line
    C = del everything to end of line and enter insert mode

    gg = top of file
    G = end of file

## Harpoon Commands

    ctrl+e = Open menu
    
    <Spc>a = Mark

    ctrl+h = Jump to file (1)
    ctrl+t = Jump to file (2)
    ctrl+n = Jump to file (3)
    ctrl+s = Jump to file (4)

# Visual Mode Commands

    v = visual mode
    V = visual SELECT mode
    ^v = visual BLOCK mode

    = = auto indent code

# LSP Commands (customized)

    <C-p> = select prev item
    <C-n> = select next item
    <C-y> = confirm
    <C-Spc> = complete


    gd = Go to Declaration
    K = Hover (?)
    <Spc>vws = Workspace symbol (?)
    <Spc>vd = Open float (?)
    [d = Go to next
    ]d = go to prev
    <Spc>vca = code action (?)
    <Spc>vrr = references (?)
    <Spc>vrn = rename
    <C-h> = signature help (?) (while in Insert mode)


