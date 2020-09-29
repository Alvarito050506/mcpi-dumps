# mcpi-dumps
MCPI Dumps, because they are too big for a Gist.

## How to generate `dump.txt`?
Use the following command:
```sh
objdump -C -t -T -r -R -D -S -g -e -s --special-syms PATH_TO_MCPI > dump.txt
```
