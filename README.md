# Self Help
self-help is a bash script example of get ops flags


## Features
- getops example ( known flags -v -h )
  - $ `self-help -h`
  ```bash
  Usage: self-help [ -h ] [ --help ]
  Options:
        -h      Print this help.
        -v      Print version info.
  ```
- Chose any filename try: 
  - $ `cp ./self-help ./libhelp && bash ./libhelp -h`
- Blinking unknown flag 
  - $ `self-help -x` 
  ```bash
  ?! Say What !?
  ```


