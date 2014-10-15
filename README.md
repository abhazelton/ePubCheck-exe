ePubCheck-exe
=============

Executable linker to epubcheck Java jar 


#Purpose of creating this
For those who have difficulty running commands and are unsure as to where their Java installation is located, etc. and need to use <a href="https://github.com/IDPF/epubcheck">epubcheck</a>, this is a simpler method of using epubcheck on Windows computers.

#epubcheck version
This download currently contains version 3.0.1, the current release.

#Usage
1. Download the zip file
2. Unzip to a location on your computer
3. Add the epub file that you want to validate into the folder where you just unzipped this, next to the ePubCheck.exe file
3. Open a command prompt window (Start > Run > cmd.exe)
4. At the command prompt, type:
```shell
ePubCheck.exe
```
If you do not have Java installed, or it can't be found on the computer, you will be notified accordingly.

#Recognition
The copy of epubcheck included with this download comes directly from [the creators](https://github.com/IDPF/epubcheck).

This executable was created using a cross-platform Java executable wrapper called [Launch4j](http://launch4j.sourceforge.net/).
