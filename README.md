# Cybersecurity notes

## Introduction

This repository contains my personal notes, solutions, and observations as I work through the cybersec curriculum. The platform covers a wide range of topics from foundational Linux skills all the way to advanced exploitation techniques. These notes are meant to help me review concepts and track my progress.

## Index

- [Assembly Foundations](#assembly)

---

## Assembly Foundations

Assembly is a language based on mnemonics that simplifies the programming process of computer code.

### List of registers

| Register | Name               | Main Function / Purpose          | Volatility   |
|:---------|:-------------------|:---------------------------------|:-------------|
| **RAX** | Accumulator        | Returns, Syscall ID, Arithmetic  | Caller-saved |
| **RBX** | Base               | Base pointer for data indexing   | Callee-saved |
| **RCX** | Counter            | Loop counter, 4th Argument       | Caller-saved |
| **RDX** | Data               | I/O, Multiply/Divide, 3rd Arg    | Caller-saved |
| **RSI** | Source Index       | String source, 2nd Argument      | Caller-saved |
| **RDI** | Destination Index  | String destination, 1st Argument | Caller-saved |
| **RBP** | Base Pointer       | Stack frame base (Local vars)    | Callee-saved |
| **RSP** | Stack Pointer      | Top of the stack                 | Callee-saved |
| **R8** | General Purpose    | 5th Argument                     | Caller-saved |
| **R9** | General Purpose    | 6th Argument                     | Caller-saved |
| **R10** | General Purpose    | Temporary storage                | Caller-saved |
| **R11** | General Purpose    | Temporary storage                | Caller-saved |
| **R12** | General Purpose    | Long-term storage                | Callee-saved |
| **R13** | General Purpose    | Long-term storage                | Callee-saved |
| **R14** | General Purpose    | Long-term storage                | Callee-saved |
| **R15** | General Purpose    | Long-term storage                | Callee-saved |
| **RIP** | Instruction Ptr    | Next instruction address         | System       |
| **RFLAGS**| Flags Register    | Status/Condition bits            | System       |

### Register sizes

<img width="547" height="524" alt="image" src="https://github.com/user-attachments/assets/aa54357e-2a7a-482c-9f47-82bc84045a95" />


### Glossary

**Pointer**: A pointer is a register that contains a memory address to a memory location.

**Stack**: The stack is a data structure of consecutive lines of bites (0 & 1 values) that lives in the computer's memory.

**Register**

**Memory**

**CPU**

**ALU**

**UC**

**Cache**

****
