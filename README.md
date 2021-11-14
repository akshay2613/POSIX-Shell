# POSIX Shell

A very simple, custom UNIX shell based on POSIX architecture with low level system calls.

## POSIX Shell supports the follwing features:
- A prompt that displays the username, hostname, and the working directory.
- Piping, and redirection
- User defined commands: `echo`, `pwd`, `cd`, `ls`, `pinfo`, `clear`, `quit`, `setenv`, `unsetenv`, `jobs`, `kjobs`, `history`, `cronjob`, `fg`, `bg`.
- Signal handling for `SIGINT` and `SIGTSP`.
- Process management that includs switching between foreground and background processes.
