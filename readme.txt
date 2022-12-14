-------------------------------------------README------------------------------------
This project is to design a simple File System which makes the following assumptions:
   The File system resides on a disk that is 128 KB in size.
   There is only one root directory. No subdirectories are allowed.
   The File system supports at most 16 files.
   The maximum size of a file is 8 blocks where each block is 1KB in size.
   Each File has a unique name.

Implemented the following operations for your file system.
  create(char name[8], int size): create a new file with this name and with these many blocks. (You can assume that the file size is specified at file creation time and the file does not grow or shrink from this point on)
  delete(char name[8]): delete the file with this name
  read(char name[8], int blockNum, char buf[1024]): read the specified block from this file into the specified buffer; blockNum can range from 0 to 7.
  write(char name[8], int blockNum, char buf[1024]): write the data in the buffer to the specified block in this file.
  ls(void): list the names of all files in the file system and their sizes.

  ----------------------------------------INSTRUCTIONS-------------------------------------
    Run the .cpp code and perfrom teh actions as directed.
