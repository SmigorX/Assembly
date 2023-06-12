> as hello_world.s -o hello_world.o

Makes 'hello_world.s' (file with our assembly code) into an object 'hello_world.o'

> gcc -o hello_world hello_world.o -nostdlib -static

Compiles 'hello_world.o' object into 'hello_world'
- '-nostdlib' excludes c libraries from being imported
