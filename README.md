# linux-cheat-sheet

- To "wrap" text at a certain number of characters, that is, make each line no more than a certain number of characters

`fold -w 80 -s my_text_file.txt`

- To directly save that output to a new file:

`fold -w 80 -s my_text_file.txt > my_text_file_wrapped.txt`
