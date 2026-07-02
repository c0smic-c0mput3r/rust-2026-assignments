# Solution notes: Group anagrams

## Approach

for each word i lowercased it, sorted the chars, joined them back as a string to make a key. words with same key are anagrams. grouped them in a HashMap and collected all values at the end.