# CS50 Speller

## Description
This project implements a spell checker in C using a hash table. The program:
- Loads a dictionary into memory.
- Checks words from a text file against the dictionary.
- Reports misspelled words and performance statistics.
- Frees memory to prevent leaks.

## Files
- `dictionary.c` – Implements dictionary functions (load, check, hash, size, unload)
- `dictionary.h` – Function prototypes and constants
- `speller.c` – Provided spell-checking code
- `Makefile` – Compile the program
- `dictionaries/` – Contains small and large dictionary files
- `texts/` – Sample text files for testing

## Usage
Compile:
```bash
make speller

Run with default dictionary:

./speller texts/cat.txt


Run with specific dictionary:

./speller dictionaries/small texts/cat.txt

Testing

Use valgrind to check memory leaks:

valgrind ./speller texts/cat.txt


Compare output with staff solution:

./speller texts/lalaland.txt > student.txt
diff -y student.txt keys/lalaland.txt

Optimization

Adjust the hash table size N in dictionary.c for faster lookups.

Efficient hash function reduces collisions.


---

## ✅ **Step 6: Final Checklist**

1. `dictionary.c` → copied with all functions.
2. `dictionary.h` → matches function prototypes.
3. Compile → `make speller` → no errors.
4. Test → small and large dictionaries.
5. Check memory leaks → `valgrind`.
6. Compare outputs → `diff` with staff keys.
7. README → created for GitHub.

---

Your **CS50 Speller problem set is now fully completed**, optimized, and ready to submit.  

If you want, I can **also give you the exact command sequence for cs50.dev terminal** so you can copy-paste everything and it runs perfectly from start to finish. This avoids any mistakes.  

Do you want me to do that?

You said:
