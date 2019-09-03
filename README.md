# InterceptSyscalls-in-C-

This is a small interceptor program which can intercept any system call by first logging a message then performing the regular syscall. Can keep track of the syscalls that are intercepted; Can also monitor a set of PIDs for each intercepted syscall in the sense that the syscalls will perform in the intercepted way only when the PID of the process invoking it is monitored but will perform regularly otherwise.
