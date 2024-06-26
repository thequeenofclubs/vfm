# VFM: Valerie's File Manager
VFM is a simple, yet powerful file manager which can run inside your shell. 
> Installation Instructions are located at the bottom of this file.

## Usage
Provides a set of functions for creating, renaming, moving, deleting, and searching for files and directories in a Unix-based operating system.

### Commands
The script supports the following commands:

- Create
The `create` command is used to create a new file or directory. It takes two arguments: the type of object to create (`file` or `dir`) and the name of the object.
To create a new file, run the command `vfm create file [filename]`. For example, to create a file called `test.txt`, run the command `vfm create file test.txt`.
To create a new directory, run the command `vfm create dir [dirname]`. For example, to create a directory called `testdir`, run the command `vfm create dir testdir`.

- Rename
The `rename` command is used to rename an existing file or directory. It takes two arguments: the current name of the object and the new name of the object.
To rename a file or directory, run the command `vfm rename [oldname] [newname]`. For example, to rename a file called `oldname.txt` to `newname.txt`, run the command `vfm rename oldname.txt newname.txt`.

- Move
The `move` command is used to move an existing file or directory to a new location. It takes two arguments: the current location of the object and the new location of the object.
To move a file or directory, run the command `vfm move [source] [destination]`. For example, to move a file called `test.txt` from the current directory to a directory called `testdir`, run the command `vfm move test.txt testdir/`.

- Delete
The `delete` command is used to delete an existing file or directory. It takes one argument: the name of the object to delete.
To delete a file or directory, run the command `vfm delete [name]`. For example, to delete a file called `test.txt`, run the command `vfm delete test.txt`.

- Search
The `search` command is used to search for files or directories by name or extension. It takes two arguments: the type of search to perform (`name` or `ext`) and the query to search for.

To search for files or directories by name, run the command `vfm search name [query]`. For example, to search for all files or directories with the name `filename`, run the command `vfm search name filename`.

To search for files by extension, run the command `vfm search ext [extension]`. For example, to search for all files with the extension `.txt`, run the command `vfm search ext txt`.

## Installation
### Method 1: Install VSH
VFM is bundled with VSH, which has a dedicated install script which simplifies the installation process substantially. You can install VSH by [visiting it's repo](https://github.com/thequeenofclubs/vsh) and following the instructions there.
### Method 2: Manual Installation
If you don't want to install VSH, you can run VFM from within BASH or ZSH by installing it manually.
**Steps:**
1. Download the VFM executable from the releases page.
2. Create a folder in your home folder called ~/Scripts
3. Add the scripts folder to the path by typing ``export PATH=$PATH:~/Scripts``.
4. Move the VFM executable into the Scripts folder you just created.
5. Restart your shell for the changes to take effect.
