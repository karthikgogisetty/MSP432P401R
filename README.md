# 🧪 Labs MSP432P401R - Assembly Programming Exercises

This repository contains simple assembly language programs demonstrating arithmetic operations at the bitwise level. These exercises are likely aimed at understanding 64-bit and 96-bit number operations using **x86 assembly language**, potentially written for the NASM assembler.

![image](https://github.com/user-attachments/assets/2990b16e-8112-4dfe-a56c-01df882b5b29)

---

## 🔧 Files & Descriptions

### `Add2_96bit_nums.s`
Performs addition of two 96-bit integers using segment-wise 32-bit arithmetic.

### `subtract2_64bit_nums.s`
Implements subtraction of two 64-bit numbers, managing borrow and underflow conditions.

### `revsub_suresh.s`
An alternate approach to subtraction — possibly reverse subtraction, or authored by a contributor named Suresh.

---

## 📦 Requirements

- NASM (Netwide Assembler)
- Linux or Windows (with DOSBox or NASM-compatible environment)

---

## ▶️ How to Run

```bash
nasm -f elf64 Add2_96bit_nums.s -o add.o
ld add.o -o add_exec
./add_exec
/* Replace Add2_96bit_nums.s with the respective filename to compile and run others. */
