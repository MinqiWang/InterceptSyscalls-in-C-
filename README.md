# InterceptSyscalls-in-C-

This is code for kernel programming. Running this program directly on a machine might cause kernel crash. Please be careful running this.

This is a small interceptor program which can intercept any system call by first logging a message then performing the regular syscall. Can keep track of the syscalls that are wanted to be intercepted;Can also monitor a set of PIDs for each intercepted syscall in the sense that the syscalls will perform in the intercepted way only when the PID of the process invoking it is monitored but will perform regularly otherwise.
