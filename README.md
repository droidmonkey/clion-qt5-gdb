# Qt Pretty Printers for MSYS2 and CLion
This is a repository that copies the Qt5 pretty printers from
KDevelop and organizes them such that CLion can load them.

CLion does not recognize a ```.gdbinit``` file located in the MSYS2
user's home directory. This requires overwriting the file stored
in ```/mingw[32|64]/etc```.

NOTE: Every time gdb (or gcc) is updated you will need to reinject the
python code into ```.../etc/gdbinit```.