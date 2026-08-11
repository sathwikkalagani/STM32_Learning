Day 01 — STM32 & C Learning
🔹 STM32 Learning
Learned STM32 project creation and build process.
Understood Targeted Project Type and why Empty can be selected.
Understood how to compile/build an STM32 project.
Learned about ITM (Instrumentation Trace Macrocell).
Learned about SWV (Serial Wire Viewer) and its working principle.
Understood the limitation of ITM/SWV with Cortex-M0.
Learned about different ways to get printf() output from the target:
SWV/ITM
OpenOCD
Semihosting
Understood that these approaches provide output through different mechanisms.
Hardware
STM32F401RBT6 board available for practice.
Will use the board for hands-on STM32 learning.
🔹 C Programming
Phase 1 — C Fundamentals ✅
C introduction
Structure of C program
main()
Header files
printf() / scanf()
Variables and constants
Keywords and identifiers
Data types
Format specifiers
sizeof()
Type casting
Signed vs unsigned
Integer ranges
Overflow and underflow
Compilation Stages ✅
.c
 ↓
Preprocessor
 ↓
.i
 ↓
Compiler
 ↓
.s
 ↓
Assembler
 ↓
.o
 ↓
Linker
 ↓
Executable
Phase 2 — Operators 🔄

Completed:

Arithmetic operators
Relational operators
Logical operators
Assignment operators
Increment/decrement operators
Ternary operator
Bitwise AND &
Bitwise OR |
Bitwise XOR ^
Bitwise NOT ~
Left shift <<
Right shift >>
Embedded C / Bitwise Practice
reg & (1 << n);     // check bit
reg |= (1 << n);    // set bit
reg ^= (1 << n);    // toggle bit
reg &= ~(1 << n);   // clear bit
Current Status
STM32 Learning       → SWV/ITM, OpenOCD, Semihosting ✅
C Phase 1            → COMPLETE ✅
C Phase 2            → Bitwise completed; final operator topics remaining 🔄

