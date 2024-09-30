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

    w|W = jumps forward to start of word (caps to ignore punc)
    e|E = jumps to end of word (caps to ignore punc)
    b|B = jumps backward to the start of previous word (caps to ignore punc)
    ge|gE = jumps backward to the end of a word (same caps behavior)

    f<character> = move cursor to next occurance of character

    A = enter insert mode at the end of your current line
    C = del everything to end of line and enter insert mode

    gg = top of file
    G = end of file

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


