# Project 7
# Recommended steps to proceed for this project
- Read [the example here](https://github.com/sklaw/enee447project7_hw_template_Shuangqi_sessions/blob/master/kernel.c#L36-L60) to learn how to use the SD card API

- Read/implement these places so that you know how a thread is started from USR mode:
  - https://github.com/sklaw/enee447project7_hw_template_Shuangqi_sessions/blob/master/shell/z_shell.c#L120
  - https://github.com/sklaw/enee447project7_hw_template_Shuangqi_sessions/blob/master/shell/u_syscalls.c#L119-L132
  - https://github.com/sklaw/enee447project7_hw_template_Shuangqi_sessions/blob/master/trap_handlers.c#L133-L142
  - https://github.com/sklaw/enee447project7_hw_template_Shuangqi_sessions/blob/master/threads.c#L85
- How to test: 
  - Test `shell`
    - modify [this line](https://github.com/sklaw/enee447project7_hw_template_Shuangqi_sessions/blob/master/kernel.c#L107) so that `shell.bin` would be loaded into memory correctly.
  - Test `app1`
    - fix up the start address of `app1`: https://github.com/sklaw/enee447project7_hw_template_Shuangqi_sessions/blob/master/app1/memmap#L4
    - try to start `app1` from shell as described in p7.pdf
  - Test `app2`
    - simiar to `app 1`
  
