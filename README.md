# AddReferenceDotRedTeam
Repo for software Lib to test dotNet red stuff in VS like a developer. 

Also this is SUPER EARLY STAGE right now! Its barley tested. This means im taking input on design and such also.

<img src="https://github.com/ceramicskate0/AddReferenceDotRedTeam/blob/master/Logo.PNG" width="350" height="300">

# Summary and Why:

In Visual Studio with C# you can import ["References" or "Extensions"](https://docs.microsoft.com/en-us/visualstudio/ide/how-to-add-or-remove-references-by-using-the-reference-manager?view=vs-2019) by right clicking and selecting ["Add Reference"](https://docs.microsoft.com/en-us/visualstudio/ide/managing-references-in-a-project?view=vs-2019). 

What this repo will be is a simple DLL or Libary for a Red Teamers to use when creating .Net stuff. Just like in developer would, this will reduce coding time and allow for quicker stuff creation. Also it makes my life easier as the tools guys/exploit dev when creating stuff in .Net. A special thanks to everyone in my [TheCollective](https://github.com/ceramicskate0/TheCollective) Repo. Your open source works helped me out alot with some of the methods, classes, and code used. 

I am hoping this will be similar to [TheCollective](https://github.com/ceramicskate0/TheCollective) Repo only for .Net or C# stuff. Im not looking for tools (preferably, but if its a class i wont object) Im looking for methods and techniques that can be thrown together when creating tools. You know like a developer would do and not a scripter. I found most Red Team frameworks, tools, etc.. are nothing more than scripts and not very modular or flexable. But you can add them to the Lib (explained below "Adding to a Lib") The goal of this project is to change that. 

# How to get it to work:

As with all C# tools compile and load yourself. But with doing it this way its super easy.
Hint Project-to project references

# Contribute:

If you want to add your favorite way to do somehting. Submit a pull reuqets and or open and issue.

# Adding to a Lib:

If you want to add lets say [SharpUp](https://github.com/GhostPack/SharpUp) to the LIB because you want to add its functionality to you assembly. Not and issue, well not a big one. 
- You can do this by adding it as a class to the Project. 
- Changing any Main method to somehting you want. 
- Making all methods and the class public then fixing any syntax or import issues you have by adding them to the project.

# [Special thanks and Credits:](https://github.com/ceramicskate0/TheCollective/blob/master/Lists/dotNET_Assembly_Payloads.txt)
I didnt create ALL of the code here. Again this is a combination of works from across the open source community. If you think I have missed any credits please add them where you wish in a pull request. I have given credits to everyone I know of in the list above.

# Legal Disclaimer:

I dont recommend or condone using anything on here for any reason. The scipts here may work, but are just as likely have a chance to break the system they are run on. If you use them you do so at your own risk. I do/have NEVER authorized,condoned, or recommend the use of anything in any of my repos for any reason, even if previously stated. This is a collection of simple code I found useful with my own Kali OS for educational purposes only. All credit goes to the authors whos full URL and/or github account and/or Repo is listed in the section above, please see their sites for more info or issue with their repo's. It should be noted that since these are all publically available. Do not use for evil, malicious purposes, or on machines you do not own.


This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>
