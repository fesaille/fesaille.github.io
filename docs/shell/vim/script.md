# Vim script

## Options

**Set options**: `set` or `se`

<badge-doc href="https://vimhelp.org/options.html#set-option" message="options" logo="vim"></badge-doc>



| Cmd                | Comment                                                                                            |
|--------------------|----------------------------------------------------------------------------------------------------|
| `:se[t][!]`        | show all options that differ from the default value, `!` forces printing to new line               |
| `:se[t][!] all`    | show all but terminal options, if `!`: every option is on a separate line.                         |
| `:se[t] {option}?` | show value of option                                                                               |
| `:se[t] {option}`  | Toggle option: set, switch it on.<br/> Number option: show value. <br/> String option: show value. |



## Variables

Scope:


| Scope             | Identifier | Comment                                     |
|-------------------|:----------:|---------------------------------------------|
| buffer-variable   |     b:     | Local to the current buffer.                |
| window-variable   |     w:     | Local to the current window                 |
| tabpage-variable  |     t:     | Local to the current tab page.              |
| global-variable   |     g:     | Global.                                     |
| local-variable    |     l:     | Local to a function.                        |
| script-variable   |     s:     | Local to a Vim script.                      |
| function-argument |     a:     | Function argument (only inside a function). |
| vim-variable      |     v:     | Global, predefined by Vim.                  |
