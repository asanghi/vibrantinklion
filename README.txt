Before the release of OS X Lion, Terminal could not handle nicer 256bit colors. So, you had to use SIMBL and then a TerminalColours plugin and then a Vibrant Ink Configuration to get super colours.

Now however, Terminal App in Lion has the ability to pick colors in 256 bits. So the only thing you need to do is import the attached file.

Cheerios,
Aditya

PS. You could then remove the ~/Library/Application Support/SIMBL/Plugings/TerminalColo*.bundle if you want.

By the way, if you get the error that some of your Terminal SIMBL plugins are not being loaded, you need to go hack the Info.plist and ensure the maximum compatible version is 297. 
Recording it here for my own reference. 

November 27, 2011

Adding Vibrant Ink Theme for iTerm2 app.
