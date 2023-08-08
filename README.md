# linux-cheat-sheet

- To "wrap" text at a certain number of characters, that is, make each line no more than a certain number of characters

`fold -w 80 -s my_text_file.txt`

- To directly save that output to a new file:

`fold -w 80 -s my_text_file.txt > my_text_file_wrapped.txt`

- To create a symbolic link:
  `sudo ln -s /usr/bin/vim /usr/bin/vi` // whenever you need to use Vi, it will point you to Vim

