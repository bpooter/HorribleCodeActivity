# Fortune Teller Project

# Overview

This project contains two versions of a fortune teller program:

- 'bad_main.py' -> intentionally overengineered version
- 'main.py' -> simplified refactored version following YAGNI principles

The goal is to demonstrate how unnecessary features and complexity can make code harder to maintain.

---

# bad_main.py (Overengineered Version)

This version demonstrates violations of the YAGNI, KISS, and seperation of concern principles as well as poorly documented with comments.

# Issues:
- Includes unnecessary features (astrology, tarot, palm reading)
- Uses a menu system to select fortune type
- Contains large hardcoded datasets (e.g., full tarot deck)
- Mixes input, logic, and output in multiple functions
- More complex than the problem requires

The program is significantly more complicated than needed for a simple fortune generator.

---

# main.py (Good Version)

This version follows the YAGNI, KISS, and seperation of concern principles and is easy to follow through comments and logic.

# Characteristics:
- Single responsibility per function
- No unnecessary features
- Simple random fortune selection
- Clear and linear program flow
- Easy to read and maintain
