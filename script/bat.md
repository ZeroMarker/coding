- command

    - echo [{on|off}] [message]
    - @ forbid echo @[message]
    - pause [message]
    - call [Drive:][Path] FileName [BatchParameters] [:lable] [arguments]
    - type [file] preview
    - rem [comment]
      - ::
      - @rem
    - set parameter set x='c:\'  %x% set [/a [expression]] [/p [variable=string]]
        -   /a 5+2 var=4/2
        -   /p var=input
    - goto jump goto [lable]	:lable [message]
    - start new window start ["title"] [/dPath] [/i:] [/min] [/max][{/separate|/shared}][/wait]
        -   dirve, file, folder, web, program
        -   /min
        -   /max
        -   start "" "ab cd"
    -   sort
    -   redirect
        -   >   write
        -   >>  append
        -   <   read
    - if 
    - else
    - for