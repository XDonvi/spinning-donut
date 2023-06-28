# spinning-donut
ASCII Art program of a spinning donut

for compiling:
```
gcc -lpthread -std=gnu99 -lm donut.c -o donut
```
If compiling with Windows, make sure that you have the library pthreads installed in your gcc compiler, otherwise it will not work.
more info [POSIX Threads for Win32](https://www.sourceware.org/pthreads-win32/)
