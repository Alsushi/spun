+++
title= "debug C programs"
date= "2019-09-19T16:58:58-05:00"
Description= "how to use gdb debug"
Tags= ["gdb"]
Categories= ["code debug"]
+++

##### how to debug c programs
Once a C file is compiled it can be debugged.
To do so will requires to improve compilatation by using
gcc -g3 file.c
then we start our program with adding a gdb prefix.
gdb ./a.out
tui e
b main
run [parameters]
target record-full
s
rs
q