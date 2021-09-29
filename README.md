# Linux OS

## How i print the value of /dev/stdin, /dev/stdout and /dev/stderr.?

> nano myscript.sh
```
#!/bin/bash
echo your stdin is : $(</dev/stdin)

```
> chmod +z myscript.sh

> $ ls | ./myscript.sh

## Reference
* https://stackoverflow.com/questions/43949166/reading-value-of-stdout-and-stderr
* https://unix.stackexchange.com/questions/400849/echo-or-print-dev-stdin-dev-stdout-dev-stderr
* https://stackoverflow.com/questions/10473800/in-go-how-do-i-capture-stdout-of-a-function-into-a-string
* http://craigwickesser.com/2015/01/capture-stdout-in-go/
