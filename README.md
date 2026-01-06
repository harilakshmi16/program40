str1 = "The quick brown fox jumps over the lazy dog"
print(str1.split()) # splits by spaces
str1 = "The-quick-brown-fox-jumps-over-the-lazy-dog."
print(str1.split('-')) # splits by hyphen
Output:
['The', 'quick', 'brown', 'fox', 'jumps', 'over', 'the', 'lazy', 'dog']
['The', 'quick', 'brown', 'fox', 'jumps', 'over', 'the', 'lazy', 'dog.']
