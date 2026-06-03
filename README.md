# C++ Utility Library

A utility library built in C++ while learning Object-Oriented Programming (OOP). This project provides reusable helper functions for random number generation, key generation, array operations, text encryption/decryption, and date utilities.

## Features

### Random Utilities
- Generate random numbers within a specified range
- Generate random characters
- Generate random words
- Generate random keys
- Generate multiple keys

### Array Utilities
- Fill arrays with random numbers
- Fill arrays with random words
- Fill arrays with random keys
- Shuffle integer arrays
- Shuffle string arrays

### Character Types
Supported random character types:
- Small Letters
- Capital Letters
- Digits
- Special Characters
- Mixed Characters

### Swap Utilities
Swap values of:
- Integers
- Doubles
- Booleans
- Characters
- Strings
- Dates (`clsDate` objects)

### String Utilities
- Encrypt text using a custom key
- Decrypt encrypted text

### Other Utilities
- Generate tab spacing
- Date manipulation support through `clsDate`

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- Visual Studio

## Project Structure

```text
.
├── clsUtil.h
├── clsDate.h
├── main.cpp
└── README.md
```

## Example Output

```text
Random Number: 45

Generated Key:
ABCD-EFGH-IJKL-MNOP

Encrypted Text:
Khoor Zruog

Decrypted Text:
Hello World
```

## What I Learned

This project helped me practice:

- Classes and Objects
- Static Methods
- Enumerations
- Arrays and Strings
- Function Overloading
- Code Reusability
- Header File Organization
- Basic Encryption Concepts

## Future Improvements

- Replace `rand()` with modern C++ `<random>`
- Add template-based generic swap function
- Add file utilities
- Add unit tests
- Convert into a complete utility framework

## Author

**Abubakar Yimam (Ibnu Imam)**

Software Engineering Student passionate about C++, AI, and Backend Development.
