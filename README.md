Reading your current script to summarize it accurately.

Read [](file:///c%3A/Users/acer/Desktop/Coding/Python/Sets.py)

## Code Summary

This script demonstrates Python set operations using two friend groups and a car list.

- `friends` and `my_friends` are defined as sets of names.
- `cars` is a list containing duplicate entries.

The script then:
1. Checks membership with `in` to see if `"John"` and `"Eric"` appear in the first set and whether both appear in the second set.
2. Uses `union()` to combine both friend sets into a single set without duplicates.
3. Uses `intersection()` to find names present in both sets.
4. Uses `difference()` to list names only found in `friends` and not in `my_friends`.
5. Uses symmetric difference (`^` or `symmetric_difference()`) to show names that appear in exactly one set.
6. Converts `cars` to a set and back to a list to remove duplicate car names.

It’s a simple exercise showing membership tests, set combination, overlap, exclusivity, and duplicate removal.
