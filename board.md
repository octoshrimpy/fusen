---
board-title: personal todo      # optional, here or as only h1 
save-as-cols: false             # optional, defaults to false 
columns:                        # required
    - [<] icebox                # [ ] with symbol in the middle required for column names
    - [ ] todo
    - [@] doing
    - [/] blocked
    - [-] cancelled
    - [x] done

---

# personal todo

<!-- simple view (default) -->

- `[<]` task 1
  this is the body of the task. it doesnt have to be a list,
  but it does need to be indented properly.
  it can also contain subtasks:
  - `[ ]` subtask 1 
  - `[x]` subtask 2
    if there are subtasks, it will show the total vs cancelled/done
    - `[ ]` task can also be subsubtasks! 
- `[<]` task 3
- `[ ]` task 2
- `[ ]` task 4
- `[ ]` task 5
- `[ ]` task 6
- `[@]` task 8
- `[@]` task 9
- `[/]` task 7
- `[-]` task 10
- `[x]` task 11


--- 

<!-- cols view -->
## `[<]` icebox 
- task 1
- task 3

## `[ ]` todo 
- task 2
- task 4
- task 5
- task 6

## `[@]` doing
- task 8
- task 9

## `[/]` blocked
- task 7

## `[-]` cancelled
- task 10

## `[x]` done
- task 11






