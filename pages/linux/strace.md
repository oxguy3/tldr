# strace

> Troubleshooting tool for tracing system calls.

- Start tracing a specific process by its PID:

`strace -p {{pid}}`

- Trace a process and filter output by system call:

`strace -p {{pid}} -e {{system call name}}`

- Count time, calls, and errors for each system call and report a summary on program exit:

`strace -p {{pid}} -c`

- Show the time spent in every system call:

`strace -p {{pid}} -T`
