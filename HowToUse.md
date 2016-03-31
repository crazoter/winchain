## What is winChain Builder? ##

What it is: It's the easiest possible way to build the iPhone toolchain on a Windows XP/Vista computer. It's a GUI installer for the toolchain which can completely install the whole thing in minutes, as opposed to sitting in front of a bunch of DOS windows trying to build thousands of source code files with confusing UNIX commands.

What it isn't: It's not a magical iPhone IDE or Interface Builder or anything like that. For that kind of stuff, you'll have to wait a little longer...

## What is the iPhone Toolchain? ##

The iPhone toolchain is the bunch of programs the Dev Team and their various accomplices have put together, which can take Objective-C source code that you write using their UIKit Headers (included with winChain) and compile it into an application that you can use on your iPhone.

## How Does winChain Work? ##

  1. Download winChain from the Downloads section, and then the preBuiltToolchain file [here](http://tinyurl.com/2vtug9).
  1. Download WinRAR from http://www.rarlabs.com and use it to extract the preBuiltToolchain. Be sure to right-click the RAR and **choose "Extract Here"** not "Extract to preBuiltToolchain" or any of the other options!
  1. Launch winChain.exe and browse to your preBuiltToolchain folder.
  1. Hit the first button to copy over the files.
  1. Hit the second button to install Cygwin.
  1. Hit the third button if you want to install Notepad++ for code-writing.

> And you're done!

## How Do I Make Projects? ##

winChain also comes with the winChain Template Generator, which you can use to create a skeleton application that you can write code into and then build easily. Just launch the generator, give it your Name and your Application's Name, choose a folder to put it in ("iphone-apps" in your cygwin folder recommended, or you'll have to edit your Makefile!), and it will make the project for you.