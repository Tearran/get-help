# Get Help
get-help is a bash script example of get ops flags

## Features
- getops example ( known flags -v -h )
  - $ `get-help -h`
  ```bash
  Usage: get-help [ -h ] [ --help ]
  Options:
        -h      Print this help.
        -v      Print version info.
  ```
- Chose any filename try: 
  - $ `cp ./get-help ./libhelp && bash ./libhelp -h`
- Blinking unknown flag 
  - $ `get-help -x` 
  ```bash
  ?! Say What !?
  ```
