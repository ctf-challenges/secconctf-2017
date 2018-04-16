Connect to the server and read "word.txt" on current directory.
$ echo '$g#67+' | nc micro.pwn.seccon.jp 10000

The server is running on GDB simulator with special patches.
Long time connection will be disconnected automatically. (in several minutes)
Short interval requests will be also ignored. (in several seconds)

---- information ----
Reference:
* About SOP
https://www.slideshare.net/kozossakai/possibility-of-arbitrary-code-execution-by-steporiented-programming

* Assembly samples for many architectures
http://kozos.jp/books/asm/cross-gcc494-v1.0.zip

See the assembly samples.
$ unzip cross-gcc494-v1.0.zip
$ cd cross-gcc494/sample
$ ls *.d

See the sample programs running on GDB simulator.
$ cd cross-gcc494/exec
$ ls *.d

* Files of the old server using SOP to solve it
(at SECCON2016 final competition)

- Information for the server
http://kozos.jp/seccon/2016/final/gdb-server/index.html

- Files of the server
　http://kozos.jp/seccon/2016/final/gdb-server/server.zip

- Files for answer
http://kozos.jp/seccon/2016/final/gdb-server/answer.zip