# Simple project checking proper environment configuration for workshops

Clone repository with **--recurse-submodules**  flag

```console
user@server:~$ cd Environment 
user@server:~/Environment$ mkdir build && cd build 
user@server:~/Environment/build$ cmake .. 
user@server:~/Environment/build$ make
user@server:~/Environment/build$ ./SimpleProject/SimpleProject_UT
[==========] Running 3 tests from 1 test suite.
[----------] Global test environment set-up.
[----------] 3 tests from TestSimpleProject
[ RUN      ] TestSimpleProject.emptyCommandThrowsException
[       OK ] TestSimpleProject.emptyCommandThrowsException (1 ms)
[ RUN      ] TestSimpleProject.wrongCommandThrowsException
[       OK ] TestSimpleProject.wrongCommandThrowsException (0 ms)
[ RUN      ] TestSimpleProject.correctCommandSendInd
[       OK ] TestSimpleProject.correctCommandSendInd (0 ms)
[----------] 3 tests from TestSimpleProject (1 ms total)

[----------] Global test environment tear-down
[==========] 3 tests from 1 test suite ran. (1 ms total)
[  PASSED  ] 3 tests.
```

