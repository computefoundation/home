
# Examples

### Find all files matching a name recursively

This problem is founded on a core aspect of all file management systems: the relationship between files and directories. To solve it, a file search program is needed, such as GNU *find*. *Find* can solve this problem with the following command:

    `find <directory to search> -type f "*<file name>*"`  
&ensp;  
As *find* searches for files and directories by default, the option `-type f` is used to find only files. Importantly, it is specific to the architecture of *find*. Nonetheless, this solution respects the Unix philosophy as it solves a problem based on a basic concept of computing: file management. As a result, it dissociates the architecture of GNU *find* from general-purpose computing.

### Execute a command in a terminal emulator (from other software)

Application windows are implemented in practically all operating systems and a good representation of what applications are, programs that accomplish specific tasks without communicating with other applications. As a result, application windows are a basic concept of computing and therefore, problems based on this concept respect the Unix philosophy. These problems include application communicability, which is still beneficial in several cases despite the specific use cases of applications. One such problem is executing a command in a terminal emulator (from other software). As a solution to this problem respects the Unix philosophy, it dissociates the architecture of the X Window System from general-purpose computing.

### RDBMS function for a database project (e.g. MySQL)

The relational database management system (RDBMS) is the most commonly used database management system and as a result, a basic concept of computing. Some of the problems relating to it are creating, deleting and exporting databases and droping and clearing data from tables. Many database projects implement the RDBMS, however, each has its own implementation and as a result, solves these problems differently. As the RDBMS is a basic concept of computing, RDBMS solutions for these different database projects respect the Unix philosophy and therefore dissociate their architecture from general-purpose computing.
