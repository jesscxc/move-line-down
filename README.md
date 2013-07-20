move-line-down
==============

# Use Sublime Text to Move a Line To Bottom of File


I have a long file of quotes. I want to move specific ones to the bottom, then return to the same spot in the text file.

You can download the .sublime-macro file and put it in any Sublime Text package folder. It will show up under Tools | Macros | (PackageName). For instance, you can put it in Sublime Text's /Packages/User folder.

If you have a Mac and want to create the macro from scratch, the instructions are below.


To activate the F2 key, remember to hold the 'fn' key in the very bottom left of the keyboard while hitting the F2 key.

When you are first recording the macro, put the cursor at the start of the line you want to copy to the bottom.

CTRL+Q; start recording macro

CMD+F2; toggle bookmark

SHIFT+DownArrow; highlight line

CMD+X; cut line (move)

CMD+DownArrow; go to bottom of file

CMD+V; paste line

SHIFT+F2; go to previous bookmark

CMD+SHIFT+F2; clear bookmark

CTRL+Q; stop recording macro

Now put the cursor in front of the line you want to copy and move down and:
CTRL+SHIFT+Q; activate macro

Hope that's useful!


2013-07 | 
Jesse Cummins | 
https://github.com/jessc
