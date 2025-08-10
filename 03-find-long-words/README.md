# Extract Long Words from Text Using Set Comprehension

## Overview
This project demonstrates how to extract unique words that have more than 5 letters from a given text using Python's set comprehension.  
The process involves cleaning the text, splitting it into words, and filtering words based on length.


## Steps Explained

1. **Replace punctuations with spaces**  
   To simplify word extraction, all punctuation marks in the text are replaced with spaces.

2. **Split the text into words**  
   Using the `.split()` method, the cleaned text is converted into a list of words.

3. **Extract long words using set comprehension**  
   Finally, set comprehension is used to extract unique words that contain more than 5 letters.

## Example
```python
text = "This is a sample sentence, to demonstrate the extraction process."
# After processing, output will be:
# {'sample', 'sentence', 'demonstrate', 'extraction', 'process'}
