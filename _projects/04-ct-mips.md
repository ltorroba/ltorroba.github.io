---
title: "Compilers and Emulators"
excerpt: "For the <i>Compiling Techniques</i> course at Edinburgh, I built a C to MIPS compiler using Java. Somewhat related, I also implemented a simplified MIPS emulator."
image: "/images/500x300.png"
collection: projects
---

For the _Compiling Techniques_ course at Edinburgh, I built a C to MIPS compiler using Java (in reality, it only supported a subset of C). This was broken down into a parser, AST builder, semantic analyzer and assembler. I also implemented a lot of tests for this, which ultimately helped a lot during development. I can share this upon request.

Somewhat related, I also built a [tiny MIPS emulator](https://github.com/ltorroba/mips-emulator), using test-driven development. It doesn't implement the whole ISA, but it allows simple programs.
I did this before the compiling techniques course, after being exposed to MIPS during my first year at university.
Ultimately my goal was to use this to power a virtual world where you could write code in C, compile it into MIPS, and execute it (something like [Screeps](https://screeps.com/)), but it turned out to be much harder than I anticipated: I was hoping to be able to use off-the-shelf compilers but the resulting binaries had much more than just the "code."
In retrospect, I could probably have just used the compiler I built sometime later.
