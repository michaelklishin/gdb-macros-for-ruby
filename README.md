A collection of macros for GNU debugger (gdb), useful for
inspection of Ruby processes.

Originally written by Jamis Buck and Mauricio Fernandez,
collected by Phillippe Hanrigou.

And slightly improved by @the83 and @ebenoist

Command         | Description
--------------  |------------
reval           | Evaluate an arbitrary Ruby expression from current gdb context.
rb_bt           | Print the ruby stack trace interpreting backtrace as a Ruby array of string.
rb_raise        | Raise a Ruby exception from gdb.
redirect_stdout | Hijack Ruby $stdout and redirect it to /tmp/ruby-debug-<pid>.
restore_stdout  | Restore Ruby $stdout to its original value after hijacking it>
rb_finish       | Execute the current Ruby method until it returns and interrupts th>
rb_object_counts| Count and print all living objects by type.
rb_locals       | Print local variables and their values.
rb_backtrace    | Print the Ruby backtrace.
rb_classname    |
rb_p            |
rb_help         | Print a list of all ruby macros



