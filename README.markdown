##DCPU16 Test Environment

Basically, a little thing i setup that might be useful to some people.
Will create and download needed files on first run.

1. Create a little endian binary version of your DCPU16 executable
2. Invoke the emulator using the "dcr.py" (Dcpu Copy and Run) file using the following syntax;
		dcr.py [binary_file.*]
3. the current file will be deleted, and the one specified will be copied into place. the emulator will then be run

P.S: if no file is specified, the program will copy into place the sample provided by notch
P.P.S: The sample executable, "hello.out" is included, provided by Isharacomix and his own assembler. To use it, type "dcr.py hello.out"
	proceed by entering random text :P