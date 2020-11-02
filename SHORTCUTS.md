# Shortcuts

| Shortcut | Description                      |
|:--------:| -------------------------------- | 
| `,,w`    | Select by target key             |
| `+`      | Select selection on cursor (will use smart selection if textobj is available for filetype / code. Coming from vim-expand-region |
| `,tt`    | Vizualise code structure         |
| `,f`     | List all files in directory      |
| `gg`     | Go to beginning of file          |
| `G`      | Go to end of file                |
| `23g`    | Go to line 23                    |
| `$`      | Go to end of line                |
| `^`      | Go to beginning of line          |
| `w`      | Go to next word                  |
| `y`      | Copy selection |
| `yy`     | Copy line |
| `p`      | Paste from default register |
| `"+p`    | Paste from system clipboard |
| `d`      | Delete selection                 |
| `dd`     | Delete line                      |
| `dw`     | Delete word                      |
| `d2w`    | Delete two words                 |
| `u`      | Undo                            |
| `:w`     | Write                            |
| `:q`     | Quit                             |
| `:wq`    | Write and Quit                   |
| `/`      | Search in file                   |
| `n`      | Go to next selection (after search)      |
| `z=`     | Spellcheck                       |
| `==`     | Auto-indent                      |
| `>>`     | Indent left                      |
| `<<`     | Indent right                     |
| `,c`     | Comment                          |
| `,cu`    | Uncomment                        |
| `,cc`    | Comment selection                |
| `gq`     | Reformat line (wrap )            |
| `ctrl b` | Move back one full screen     |
| `ctrl f` | Move forward one full screen      |
| `ctrl d` | Move forward 1/2 screen      |
| `ctrl u` | Move back (up) 1/2 screen      |
| `,nt` | Toggle NerdTree |
| `,gu` | Toggle Gundo |
| `v` | Visual mode |
| `V` | Line selection |
| `V G` | select line from selector till end of file |
| `ctrl v` | Region selection (for vertical column selection) |
| `split` | Open file after horizontal split |
| `vsplit` | Open file after vertical split |
| `:CtrlP` | Open file with strong pattern matching |
| `K` | Print corresponding documentation on function |
| `:Tabularize/&` | Tabularize along & |
| `:%s/\ve/i/g` | Search and replace (s/) on whole file (%) using perl regex: all e become i. Apply to all occurences across lines (g) not just the first one |
| `:noh` | remove highlight |
| `,,w` | (leader leader w) easily nagivate through file |

## HowTo

### Comment / uncomment code block
https://stackoverflow.com/a/1676690

### Copy-paste 
Either use `:set paste` then ctlr v 
Either use `"+p` (copy from system clipboard)
To copy from vim register, do `p`
