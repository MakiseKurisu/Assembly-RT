Register
========

Unlike x86 architecture, Advanced RISC Machine (ARM) architecture is oddly enough under a RISC design, which means compared to x86, ARM has less instruction and more register in general.The first question I came up with while I was learning ARM assembly is, how those registers work? After all, there are 16 general registers, which were named from r0 to r15, and those names are anything but helpful.

Register | Alias | Note
--- | --- | ---
r0 | | Argument / Result / Scratch, EAX
r1 | | Argument / Result / Scratch, EAX
r2 | | Argument / Scratch, EAX
r3 | | Argument / Scratch, EAX
r4 | | 
r5 | |
r6 | |
r7 | |
r8 | |
r9 | |
r10 | |
r11 | | **EBP**
r12 | IP | Inter-Procedure-Call Scratch Register
r13 | SP | Stack Register, ESP
r14 | LR | Link Register, the return address for procedure
r15 | PC | Program Counter, EIP
