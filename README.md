# NCL Enumeration & Exploitation CTF Labs

## Overview

This repository documents a collection of **Enumeration & Exploitation Capture the Flag (CTF) challenges** completed as part of the National Cyber League (NCL) and CIS 4891 at Miami Dade College.

The labs focused on applying cybersecurity concepts and problem-solving techniques to analyze programs, reverse engineer application logic, identify hidden conditions, decode information, and determine valid solutions to security challenges.

The challenges provided hands-on exposure to several areas of cybersecurity, including **reverse engineering, Python bytecode analysis, binary analysis, source code analysis, debugging, ASCII encoding, cipher analysis, and exploitation concepts**.

## Tools & Technologies

Tools and technologies used throughout the CTF exercises included:

- Kali Linux
- Python
- uncompyle6
- Vim
- Ghidra
- JD-GUI
- ROT/Cipher Analysis
- ASCII & Hexadecimal Analysis
- Linux Command Line

## CTF Challenges

The Enumeration & Exploitation exercises included several different challenge types.

### Python Reverse Engineering

Compiled Python `.pyc` files were analyzed and decompiled using `uncompyle6` to reconstruct readable Python source code.

The reconstructed programs were examined to understand their validation logic and determine the conditions required to produce successful results.

These exercises involved techniques such as:

- Python bytecode decompilation
- Source code analysis
- Debugging reconstructed code
- Password-validation analysis
- ASCII character analysis
- Constraint-based problem solving

### Cipher & Encoding Analysis

Some challenges required analyzing encoded or transformed character values to determine the original information.

These exercises involved concepts such as:

- ROT substitution
- ASCII values
- Hexadecimal representation
- Character encoding
- Pattern recognition

### Java Reverse Engineering

Java-based challenges required examining compiled programs to understand their internal logic.

Tools such as **JD-GUI** were used to decompile Java applications and analyze program behavior, conditions, and embedded values.

### Binary Analysis

Binary challenges introduced reverse engineering with **Ghidra** and Kali Linux.

The exercises involved inspecting executable files, locating important functions, reviewing decompiled code, and analyzing program behavior to identify vulnerabilities or information required to complete the challenge.

## Skills Demonstrated

**CTF Analysis • Enumeration & Exploitation • Reverse Engineering • Python • Python Bytecode • Static Analysis • Binary Analysis • Ghidra • Kali Linux • Debugging • ASCII Analysis • Hexadecimal Analysis • Java Decompilation • Program Logic Analysis • Cybersecurity Problem Solving**

## Methodology

The general workflow used throughout the challenges was:

**Analyze Challenge → Identify File/Program Type → Select Analysis Tool → Inspect or Decompile Program → Analyze Logic → Identify Constraints or Vulnerabilities → Develop Solution → Validate Results**

Rather than relying solely on guessing or trial and error, the challenges required examining how each program operated and using the discovered logic to determine a solution.

## My Contribution

This CTF write-up was completed as a collaborative group project.

My individual contribution focused on the **Python 3 (Medium)** challenge.

For this challenge, I analyzed a compiled `PYTHON3.pyc` file, decompiled the Python bytecode using `uncompyle6`, reconstructed and debugged the source code, analyzed the program's password-validation logic, and identified the ASCII, character, and length constraints required to produce a valid input.

## Key Takeaways

These CTF exercises strengthened my ability to approach unfamiliar programs systematically and determine how they operate through technical analysis.

The labs provided practical experience selecting appropriate security tools, analyzing compiled programs, interpreting program logic, troubleshooting code, working with character encodings, and applying structured problem-solving techniques.

The project also provided exposure to multiple reverse-engineering technologies and demonstrated how different tools can be used depending on whether the target is Python bytecode, Java bytecode, or a compiled binary.

## Disclaimer

These challenges were completed in an **authorized National Cyber League educational CTF environment**. All enumeration, reverse engineering, exploitation, and analysis activities documented in this repository were performed for educational and cybersecurity skills-development purposes.
