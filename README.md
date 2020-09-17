# Virtual Key API

A simple C based Virtual key API reading text from the file and conver each character to WIN32 Virtual Key

## Mandatory Dependency

windows.h Required to compile the code, either wind32api in GCC or MSYS2/MinGW/Cygwin or VC++ runtime required to compile the code

## Example usage

Launch x3270 for mainframe

Example

```
x3270 -model 2 -xrm 'x3270.emulatorFont: -xos4-terminus-medium-r-normal--32-320-72-72-c-160-iso8859-1' 127.0.0.1:3270
```

Then open any file in the mainframe ISPF editor and keep the cursor in new line mode

Then run C code and immediately focus the x3270 terminal

All text inside transfer.txt will be typed inside the editor char by char

## License

MIT
