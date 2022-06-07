On Unix-like operating systems such as Linux, signals are software interrupts. They provide a way for the user (or a process) to directly communicate with a process.

Software may be programmed to respond intelligently to a wide array of signals, and certain signals cause processes to behave in a standardized, predefined way at the kernel level.

Process signals were developed as part of UNIX in the 1970s. They are used on all modern Unix-like operating systems, including Linux, BSD, and macOS X.

When a signal is sent to a process, the operating system interrupts the normal flow of the process execution and delivers the notification. If the process has previously registered a way to handle that particular signal, that routine is executed, otherwise the system executes the default signal handler.

Signals can be sent with the kill command, which is named for its default signal (SIGKILL) that instructs the OS to forcefully terminate a process before doing anything else.

Signal names are commonly abbreviated without their SIG prefix, e.g., "KILL", including in the command arguments of kill.
