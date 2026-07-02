# Solution notes: Run-length encode

## Approach

so basically i walked through the string char by char, kept track of what char im on and how many times i saw it. when it changed i pushed the old one with its count to result and started over. after the loop i pushed the last one too cuz the loop misses it.

## Edge cases handled
empty string just returns empty vec, loop never runs 

