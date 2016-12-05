# programming-language-ideas
* Pointers actually looking like pointers: `>`. Example: `>pointerVar`. Pointers are safe by default but "safe mode" can be turned off to allow advanced programming.
* Storing variable in other places than RAM: `$()` or `$`. Example: `$('path/to/dir')diskVar` or `$diskVar`. Omitting the paranthesis will result in the compiler choosing where in the disk to store the variable for you.
* Faster ways (typewise) to iterate through arrays: `arr[start_pos ... end_pos]`. Example: `str += arr[4 ... 53]`.
* Garbage Collection, can be disabled by passing arg. `--nogc` to compiler. It will still work if you've manually collected most garbage, and can collect the ones you missed, but might increase the compilation time.
* Channels & something similar to Go's goroutines.
