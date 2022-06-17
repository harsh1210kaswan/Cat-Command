Build WCAT commands
It is used to display or make a copy content of one or more files in the terminal

General Syntax: node wcat.js [options] [filepaths] option to remove big line break (-s)  option to add line numbers to all lines (-n)

Commands:

1- node wcat.js filepath => displays content of the file in the terminal ✔<br>
2- node wcat.js filepath1 filepath2 filepath3... => displays content of all files in the terminal in (contactinated form) in the given order. ✅<br>
3- node wcat.js -s filepath => convert big line breaks into a singular line break<br>
4- node wcat.js -n filepath => give numbering to all the lines<br>
We can mix and match the options.<br>

Edge cases:

1- If file entered is not found then it gives file does not exist error. ✅<br>
