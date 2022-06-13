# 1. How do I get a shell???

When booting CQX96, you may see the message “No shell found! System halted.”,

This is because you do not have a shell in your filesystem, to add a shell, open your USB drive (or Image, or whatever you are storing CQX96 on)

and add a shell called SH.PRG (see 1.1).

# 1.1. I created SH.PRG, now the system hangs!!!

You shouldn't just create SH.PRG, you need to add a compiled shell, to create your own shell

you can visit the [example shell](https://github.com/CQX96/cqx96-apps/blob/main/shelltemplate.asm) page, and

compile that code using nasm, rename the compiled code to SH.PRG, and move it to your installation.

# 1.2. Why is there no default shell?

Because CQX96 is not a full operating system!

CQX96 only has a kernel and bootloader, no shell or programs.
