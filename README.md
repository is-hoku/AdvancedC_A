# AdvancedC_A
This is a support tool for NITTC students taking Advanced C Programming A using Linux and Vim.
## vs2vim   
Most of files handed out by the teacher are Visual Studio and Windows format, which was inconvenient for working on exercises and homework.   
Then I made this shell script which convert cpp file properly.   
This shell script solved that problems by replacing ¥ with backslash and Shift_JIS with UTF-8.  
It automates the proper conversion of files, moving files from /Downloads to the current directory. In other words, just type a command and you'll be ready to work on your exercises and homework.
```
$ vs2vim [file_name]
```
*Note: Please enter the file name, not the file path.
