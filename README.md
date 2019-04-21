# Colorc - A Simple Header File To Provide Color Printing

<br>

## Install

Install by [clib](https://github.com/clib/clib):

## Example

```
$ clib install WestleyR/colorc
```

```c

#include <stdio.h>

#include "colorc/colorc.h"

int main() {
    printf("%sHello World, (red)%s\n", RED, COLOR_RESET);
    printf("%sHello World, (green)%s\n", GREEN, COLOR_RESET);

    return(0);
}
```

Then add `CFLAGS += -I deps` to your Makefile.

<br>

## License

```
The Clear BSD License

Copyright (c) 2019 WestleyR
All rights reserved.

This software is licensed under a Clear BSD License.
```

<br>
