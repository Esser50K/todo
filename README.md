# todo
A simple todo application for the terminal.
![preview_image](todo_preview.png)

## features:
1. create/remove tasks
2. daily occurring tasks, depending on weekday, you can always have certain tasks appear, for example:

        monday - business day             Tuesday - Optimization day
          ☑ check business mail               ☑ Add optimization tasks for today
          ☐ taxes                             ☑ Drink water

## Controls:

    [in edit mode]
    i:   enter insert mode (make new task)
    j,k: move up or down task list.
    h,l: mark task as done / not done.
    x:   remove task
    q:   close application
        
    [in insert mode]
    [Enter]: submit new task
    [Esc]:   cancel new task, enter edit mode

## License
todo is dual-licensed under either

* MIT License (docs/LICENSE-MIT or http://opensource.org/licenses/MIT)
* Apache License, Version 2.0 (docs/LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)

at your option.
