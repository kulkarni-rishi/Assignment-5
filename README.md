# Assignment-5
import re

text = input("Enter a string: ")

# Check if the string contains only a-z, A-Z, and 0-9 (non-empty)
if re.fullmatch(r"[a-zA-Z0-9]+", text):
    print("Valid: String contains only a-z, A-Z, and 0-9.")
else:
    print("Invalid: String contains other characters or is empty.")
