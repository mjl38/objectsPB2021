# Objects PB2021
A small tool to search within source code of a library list and compare 2 versions of a Powerbuilder project
***
**Here's a [video](https://drive.google.com/uc?export=download&id=1uNyK8XeO2GQmFB3AJAq5Zj_islb54ol8) which "sort of" explains how to use it.**<br><br>
The application depends on the use of any external file comparison tool which allows commandline execution. I've chosen WinMerge in this case. If you do a search on "winmerge" (without the quotes), you'll find which line of code would have to be adapted for a different tool. You'll probably also have to edit that line to start with, because my winmerge is installed on my D: drive.<br>
***
**Possible improvements:**  
- [ ] Don't use FileRead / FileWrite, use FileReadEx and FileWriteEx instead
- [ ] Don't get the library lists from TXT files, but allow to select a workspace and then a target to have the list be generated by code.
- [ ] Avoid having to edit the code to specify the location of the comparison tool (winmerge).
- [ ] The "Match" button needs to work properly.
- [ ] Make the window resizable
- [ ] Instead of using temp1.txt and temp2.txt, use filenames that include the objectname.
- [ ] Show the name of the Exported Libs I and II somewhere on the window.
