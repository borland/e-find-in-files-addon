[E-TextEditor](http://www.e-texteditor.com) is a great textmate compatible editor for windows.

In it's current version however, it lacks the capacity to perform a search across multiple files/directories.

There exist some other textmate-compatible bundle items which provide this feature, but they all seem to be basically calls out to find | xargs | grep, which is hugely slower than a native imeplementation

This project provides a standalone C# executable which is designed to act as an addon to [E-TextEditor](http://www.e-texteditor.com) and provide this facility

To Install:

Please ensure you have the .net framework 2.0 from microsoft installed.

Please Download FindInFiles.zip from the 'featured downloads' link to the right

Read and follow the instructions.txt inside that zip file

Thanks, Orion.


---


Note: I've currently been doing a LOT of refactoring of the code to implement not only find-in-files, but replace-in-files also. The current revision in SVN is not functioning yet, but the next time I get a chance to clean it up, it should be :-)


[Browse Source Code](http://code.google.com/p/e-find-in-files-addon/source/browse/#svn/trunk)