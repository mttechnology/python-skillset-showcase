# Extract Long Words from Text Using Set Comprehension

## Overview
This folder contains two Jupyter notebooks showing different ways to extract unique words from text based on their length.
- **Set Comprehension**: Finds words with more than 5 characters.
- **Closure**: Finds words longer than a user-defined length.

## Method 1 – Set Comprehension (>5 characters)
- Replace punctuation with spaces.
- Split the text into words using `.split()`.
- Use a set comprehension to extract unique words longer than 5 characters.

## Method 2 – Closure (Custom length)
- The outer function sets the minimum word length (`num`).
- The inner closure function processes the text by:
  1. Replacing punctuation with spaces
  2. Splitting the text into words
  3. Using `filter()` to select words longer than `num` characters
  4. Creating a set to return unique words
- The closure returns all unique words that meet the length requirement.









