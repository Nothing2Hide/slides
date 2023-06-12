Secure deletion
-------------------

When you delete a file, you simply remove its entry from the hard disk index. In other words, you never erase a file, but only its reference.


Once deleted, your files can be recovered using tools such as [Photorec](https://www.cgsecurity.org/wiki/PhotoRec) or [TestDisk](https://www.cgsecurity.org/wiki/TestDisk). 


To get rid of a file **really** you'll need to use secure deletion tools available on Windows, Linux, Android and Mac OS. Unfortunately not yet on iPhone.


Windows
----
[Eraser](https://sourceforge.net/projects/eraser/files/latest/download)


Linux
----
[Wipe](https://linux.die.net/man/1/wipe)


Android
-----
[Secure delete](https://play.google.com/store/apps/details?id=com.peterhohsy.securedelete)


Mac OS
------

The "Empty Recycle Bin in Secure Mode" function has been removed from OS X 10.11. Apple felt that it could not guarantee secure deletion on SSD drives.

If you're using a traditional hard disk with OS X 10.11 and can use the command line, you can use the [srm command](http://www.macworld.com/article/3005796/operating-systems/how-to-replace-secure-empty-trash-in-os-x-el-capitan.html) to overwrite the file.


If you know how to use the terminal on Mac OS, since Mac OS 10.12 you can use the command 

    rm -P

