
| **neovim**                                      | **intellij**                                        | **description**                                                         |
| ----------------------------------------------- | --------------------------------------------------- | ----------------------------------------------------------------------- |
| `gcc` vm                                        | `ctrl + /`                                          | one line comment                                                        |
| `dd`                                            | `ctrl + y`                                          | delete line (nvim copy as well)                                         |
| `alt + j`                                       | `ctrl + alt + arrow down`                           | move line down                                                          |
| `alt + k`                                       | `ctrl + alt + arrow up`                             | move line up                                                            |
| `shift + l`                                     | `alt + right arrow`                                 | select buffer/tab on right                                              |
| `shift + h`                                     | `alt + left arrow`                                  | select buffer/tab on left                                               |
| `ladder + ,`                                    | `ctrl + e`                                          | pick open buffer/tab                                                    |
| `ladder + bd`                                   |                                                     | remove/delete tab/buffer                                                |
| `ladder + sg`                                   | `ctrl + shift + f`                                  | global search for text inside files                                     |
| `ladder + ladder`                               | `shift + shift`                                     | global search for files by filenames                                    |
| `ladder + sk`                                   |                                                     | search shortcuts                                                        |
| `ctrl + wh`                                     |                                                     | focus file explorer when already open                                   |
| `ladder + e`                                    |                                                     | toggle file explorer                                                    |
| `a` when directory in file explorer is selected |                                                     | create new file (with path possible) for example `stringer/stringer.go` |
| `r` when file in file explorer is selected      | `shifr + f6` when file in file explorer is selected | rename a file                                                           |
| `grr` vm                                        | `ctrl + b`                                          | go to reference                                                         |
| `Ctrl+o o` im                                   | `shift + enter`                                     | new line below                                                          |
| `Ctrl+o O`                                      |                                                     | new line above                                                          |
| `ladder + cr`                                   | `shift + f6`                                        | rename inside file(s?)                                                  |

---

Buffer              = Tab / Open file
Window          = Editor split
Tabpage (tab) = Workspace of splits
Register          = Clipboard slot
Yank                = Copy
Delete             = Cut (to register)
Visual mode    = Text selection
Normal mode       = Command mode
Insert mode       = Typing mode
Command mode (:)  = Command palette / IDE action
Quickfix list     = Problems window
Location list     = File-local Problems window
Jump list         = Navigation history
Mark              = Bookmark
Terminal buffer   = Integrated terminal tab
LSP               = Language service
Code Action       = Quick Fix / Intention Action
Diagnostic        = Error / Warning / Hint
Treesitter        = Syntax tree / PSI tree
Text Object       = Structured selection target
Leader key        = Shortcut prefix
Motion            = Navigation command
Operator          = Action (delete, change, yank)
Macro             = Recorded editor macro
Autocommand       = IDE event hook
Plugin            = Extension
Session           = Saved workspace