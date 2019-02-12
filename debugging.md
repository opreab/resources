# GDB

```
# Run binary with arguments
gdb --args executablename arg1 arg2 arg3

# Set a breakpoint at entry to function function.
break function

# Set a breakpoint some number of lines forward or back from the position at which execution stopped in the currently selected stack frame.
break +offset
break -offset

# Set a breakpoint at line linenum in the current source file.
break linenum

# Set a breakpoint at line linenum in source file filename.
break filename:linenum

# Set a breakpoint at entry to function function found in file filename.
break filename:function


# follow parent/child fork
set follow-fork-mode [parent|child]
```
