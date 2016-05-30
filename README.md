# TrIDGUI2
a gui for TRID ( http://mark0.net/soft-trid-e.html )

This gui is made with livecode 7 ( http://www.livecode.org ), it works with Windows and Linux (and Mac if a binary is provided).

## Waht is **TrID** - File Identifier ?

TrID is an utility designed to identify file types from their binary signatures. While there are similar utilities with hard coded logic, TrID has no fixed rules. Instead, it's extensible and can be trained to recognize new formats in a fast and automatic way.

TrID has many uses: identify what kind of file was sent to you via e-mail, aid in forensic analysis, support in file recovery, etc.

TrID uses a database of definitions which describe recurring patterns for supported file types. As this is subject to very frequent update, it's made available as a separate package. Just download both TrID and this archive and unpack in the same folder.

The database of definitions is constantly expanding; the more that are available, the more accurate an analysis of an unknown file can be. You can help! Use the program to both recognize unknown file types and develop new definitions that can be added to the library. See the TrIDScan page for information about how you can help. Just run the TrIDScan module against a number of files of a given type. The program will do the rest.

Because TrID uses an expandable database it will never be out of date. As new file types become available you can run the scan module against them and help keep the program up to date. Other people around the world will be doing the same thing making the database a dynamic and living thing. If you have special file formats that only you use, you can also add them to your local database, making their identification easier.

To get you started, the current library of definitions is up to 6880 file types and growing fast.

TrID is simple to use. Just run TrID and point it to the file to be analyzed. The file will be read and compared with the definitions in the database. Results are presented in order of highest probability. 
