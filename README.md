# mastiff

Mastiff is an implementation of the famous Bulldog VLIW compiler in the Rust programming language.

## What's VLIW?

VLIW, or [Very Long Instruction Word](https://en.wikipedia.org/wiki/Very_long_instruction_word) architectures are a class of instruction set architectures which utilize very long instruction words (sometimes as large as 512 bits, as in the case of Fisher's [ELI-512](https://courses.cs.washington.edu/courses/cse548/16wi/Fisher-VLIW.pdf) architecture). This added bitwidth in each instruction word allows for fine-grained parallelism by encoding independent, concurrent instructions for each functional unit within a processor.

While VLIW general-purpose processors have come and gone (see, for instance, [Multiflow's Trace](https://link.springer.com/referenceworkentry/10.1007/978-0-387-09766-4_8) and [Intel's Itanium processors](https://en.wikipedia.org/wiki/Itanium)), VLIW processors are still commonly used for DSP applications, where program structures lend themselves well to trace-scheduling optimizing compilers and short programs can be developed by domain experts for repeated use across applications. See for example [Qualcomm Hexagon](https://en.wikipedia.org/wiki/Qualcomm_Hexagon), which has a backend built into LLVM.

## What's Bulldog?

Bulldog was the first VLIW compiler, developed by John Ellis at Yale in 1985. 

## Why are you doing this?

First, the history of VLIW is fascinating. 

...



