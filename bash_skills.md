#Bash skills#

Today I will record some skills in this article!

    $ ehco abc aaa dde
    bash: ehco: command not found 
    $ ^ehco^echo
    echo abc aaa dde
    abc aaa dde
This is my favorite skill '^string^string2' which takes the last command, replaces string with string2 and executes it.

Renaming/moving files with fuffixes quickly:
    
    cp /home/foo/reallylongname.cpp{, -old}
This expands to: 
    cp /home/foo/reallylongname.cpp /home/foo/reallylongname.cpp-old

Rename the file.
    ``bash
    $ ls 
    this_has_text_to_find_1.txt
    this_has_text_to_find_2.txt
    this_has_text_to_find_3.txt
    this_has_text_to_find_4.txt
    this_has_text_to_find_5.txt

    $ rename 's/text_to_find/been_renamed/' *.txt
    $ ls
    this_has_been_renamed_1.txt
    this_has_been_renamed_2.txt
    this_has_been_renamed_3.txt
    this_has_been_renamed_4.txt
    this_has_been_renamed_5.txt
That so useful!


