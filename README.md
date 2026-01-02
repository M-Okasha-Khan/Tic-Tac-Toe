# Tic Tac Toe – 16-bit x86 Assembly (DOS)

This project is a **DOS-based Tic Tac Toe game** written in **16-bit x86 Assembly**.  
It is assembled using **NASM** and executed inside **DOSBox**.

---

## Enviorment Requirements

- Any OS (Windows / Linux / macOS)
- **DOSBox** https://www.majorgeeks.com/files/details/dosbox.html?authuser=0
- **NASM**   https://github.com/soothscier/assembly-nasm?hl=en&authuser=0
- Copy the Files in the nasm folder 

---

## Files
- tictactoe.asm
- tictactoe1.asm
- tictactoe2.asm
- tictactoe3.asm

## Running Requirements
- Copy the files in the Nasm folder
- Open the DosBox

## Instructions

- mount c "Path to the Nasm Folder"
- c:/
- nasm tictactoe.asm -o tictactoe.com -l tictactoe.lst
- tictactoe.com

## For Debugging

- afd tictactoe.com
