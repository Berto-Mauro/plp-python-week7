# Week 7 Assignment — Hands-On Lab: Shopping List Manager

This project practices Python lists, list operations, membership checking, loops, and simple list reporting.

### Files

* `list_warmup.py` — Demonstrates creating a list, accessing items by index, using `append()`, using `remove()`, and counting items with `len()`.
* `shopping_list.py` — Provides an interactive shopping list manager for adding, removing, showing, and finishing a shopping list.
* `list_report.py` — Prints a numbered shopping list, counts item names with more than four letters, and finds the longest item name using a loop.
* `screenshots/` — Contains screenshots showing the programs running and their outputs.

### Why check `in` before using `.remove()`?

Checking `in` before calling `.remove()` is safer because the item may not exist in the list. If we try to remove an item that is not in the list, Python can raise an error and stop the program. Using `in` allows us to check first and give the user a helpful message instead.
