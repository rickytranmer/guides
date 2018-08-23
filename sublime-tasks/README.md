# Sublime Todo List

## [PlainTasks for Sublime](https://github.com/aziz/PlainTasks)

### While I use VS Code as my main editor, Sublime still has its uses.  For me, that's as a note-taker and todo list.  Sublime is one of the fastest and most lightweight editors, and it lets me keep my todo list separate from my code.

#### See documentation for install and default hotkeys.

#### My hotkey changes (copy and paste):
`{ "keys": ["super+t"], "command": "plain_tasks_new_task_doc" },`
- Open a new todo doc

`{ "keys": ["ctrl+d"], "command": "plain_tasks_complete","context": [{ "key": "selector", "operator": "equal", "operand": "text.todo" }] },`
- change `Done` hotkey from CMD+D to CTRL+D

`{ "keys": ["super+d"], "command": "find_under_expand" },`
- keep the functionality CMD+D normally has
