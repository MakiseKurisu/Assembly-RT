hello world
===========

So before we go into Windows RT, let's talk about programming on this system in general.

From any point of view, Windows RT **IS** Windows 8, especially after you jailbreak it. On the other hand, Windows RT is lacking of either disktop programs or Modern apps, which is another indication that it is Windows 8!

So far, Windows RT only supports ARMv7 Thumb-2 code. No 32-bit ARM code since the kernal will always put the status bit back to Thumb (more on that later, see *Register*). No x86 code, well, natively. There is a x86 userland emulator called x86emu that runs some small programs. But the project itself is abandoned.

The PE file is same as the one that contains the x86-64 code. SEH is part of the PE file information instead using a register like what x86 does. Still, more on that later (see *Exception*).

While MASM is a super powerful assembler, ARMASM is a dumb assembler just like MASM64. However using C preprocessor we can write code much easier. Check *Macro* chapter.
