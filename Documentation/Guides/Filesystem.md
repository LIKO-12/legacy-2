## Description
The LIKO-12 file system is case-insensitive, meaning that `cd programs`, and `cd Programs`are the same. Also, it is split into two 50 megabyte drives. Note that a directory and folder are essentially the same thing in this case.

## Drives
| C: | D: |
|--|--|
| For system | For user |
| Rewritten on update | Not rewritten on update |

### Important
!> **Never** store your own things in the **C** drive, as **it is replaced on updates**.

## Paths
There are relative paths, and absolute paths. Relative paths refer to a file / directory on the same drive, and are relative to the current directory (the one shown in the prompt), while absolute paths, refer to a file / directory, on a different drive, and begin with the drive letter followed by the colon. Both types use `/` as a delimiter. A relative path can also make use of `..`, which can be used to access the parent directory.

### Examples

 - Absolute:
	 - `C:/Programs`
	 - `D:/test`
 - Relative:
 - `../other`
 - `child/dir`
## Navigation Commands

 - `ls`: Used to list contents of current directory, or a directory given as an argument.
 - `cd`	: Used to change the current directory to the path given as an argument.

## Important Directories
| Programs | Help | Games |
|--|--|--|
| used in both drives | used only in C drive | used in both drives |
| holds programs to run | holds help files (lua and plain text) | conventional place to hold games |
