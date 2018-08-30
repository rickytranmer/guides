# Sublime Todo List

## [PlainTasks for Sublime](https://github.com/aziz/PlainTasks)

#### While I use VS Code as my main editor, Sublime still has its uses.  For me, that's as a note-taker and todo list.  Sublime is one of the fastest and most lightweight editors, and it lets me keep my todo list separate from my code.

#


#### My personal hotkey changes:

-Open a new todo doc
- `{ "keys": ["super+t"], "command": "plain_tasks_new_task_doc" },`

-Change `Done` hotkey from CMD+D to CTRL+D
- `{ "keys": ["ctrl+d"], "command": "plain_tasks_complete","context": [{ "key": "selector", "operator": "equal", "operand": "text.todo" }] },`

-Keep the original functionality of CMD+D
- `{ "keys": ["super+d"], "command": "find_under_expand" },`

#

##### See [documentation](https://github.com/aziz/PlainTasks) for install instructions and default hotkeys.