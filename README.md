FHS - File Hierarchy Structure
==============================

This command is for packagers and cross-platform developers.



Description:
------------

Pass a FHS-describing DIRNAME and get it's path.

Can be used on heavily modified directory structures on a Linux-BSF (Build From Scratch), 
thanks to the use of a RC file.



Usage Examples:
---------------

   fhs cfg
   fhs --l
   fhs --list-fhs
   fhs --list-dirnames
   fhs --write-rc --default


Notes:
------
Please create a ticket/bug report on github if you have additional directories for the DIRLISTS that are used to brute-force-detect the proper/according directories.
