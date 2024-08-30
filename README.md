# Developing a Multithreaded Kernel from Scratch

The project is divided into three main sections:

- **Real Mode Development**
- **Protected Mode Development**
- **Assembly Language Bonus**

### Real Mode Development

- The boot process and how memory works
- Writing a boot loader in assembly language
- Working with interrupts in real mode
- Reading a sector (512 bytes) from the hard disk

### Protected Mode Development

The creation of a 32-bit multi-tasking kernel featuring:

- FAT16 filesystem implementation
- Memory management and virtualization techniques
- Keyboard driver implementation
- ELF file loader creation
- Design of a virtual filesystem layer (inspired by Linux kernel)
- Process and task functionality

### Require skills in:

- Creating a kernel from scratch
- Developing a multi-tasking kernel
- Handling problematic programs in your operating system
- Understanding how memory works in computers
- Differentiating between kernel land, user land, and the protection rings
- Learning kernel design patterns used by Linux
- Understanding and implementing virtual memory
- Developing processes and tasks in the kernel
- Loading ELF files
- Debugging disassembled machine code
- Debugging your kernel in an emulator with GDB

