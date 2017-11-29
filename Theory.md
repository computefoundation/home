
# Theory

General-purpose computing involves all areas of computing known by the general computer user. As a result, efficiency is considerably its most significant issue, however, it is enitrely inefficient.

Programs/software in the category of general-purpose computing are founded on abstract concepts including file management, application windows, databases, file rendering, word processing, etc. In order for general-purpose computing to be efficient, software must correspond with the UNIX philosophy, however, none does because software has architecture. As efficiency depends on the UNIX philosophy, general-purpose computing is made efficient with solutions respecting the UNIX philosophy, or in other words, to problems in the foundational level of the abstract concepts general-purpose computing is founded on. These problems include, for example, finding a file recursively, making a basic application communicable with other software or performing a basic RDBMS action on a database.

## Examples

1. **Find all files matching a name recursively.** This problem is founded on a core aspect of all file management systems: the relationship between files and directories. To solve it, a file search program is needed, such as GNU *find*. *Find* can solve this problem with the following command:

    `find <directory to search> -type f "*<file name>*"`  
&ensp;  
As *find* searches for files and directories by default, the option `-type f` is used to find only files. Importantly, it is specific to the architecture of *find*. Nonetheless, this solution respects the UNIX philosophy as it solves a problem based on a basic concept of computing: file management. As a result, it dissociates the architecture of GNU *find* from general-purpose computing.

2. **Execute a command in a terminal emulator (from other software).** Application windows are implemented in practically all operating systems and a good representation of what applications are, programs that accomplish specific tasks without communicating with other applications. As a result, application windows are a basic concept of computing and therefore, problems based on this concept respect the UNIX philosophy. These problems include application communicability, which is still beneficial in several cases despite the specific use cases of applications. One such problem is executing a command in a terminal emulator (from other software). As a solution to this problem respects the UNIX philosophy, it dissociates the architecture of the X Window System from general-purpose computing.

3. **RDBMS function for a database project (e.g. MySQL).** The relational database management system (RDBMS) is the most commonly used database management system and as a result, a basic concept of computing. Some of the problems relating to it are creating, deleting and exporting databases and droping and clearing data from tables. Many database projects implement the RDBMS, however, each has its own implementation and as a result, solves these problems differently. As the RDBMS is a basic concept of computing, RDBMS solutions for these different database projects respect the UNIX philosophy and therefore dissociate their architecture from general-purpose computing.

## Illustration

The following illustration shows the architecture-specificity of software, the extent to which its principles lose correlation with the UNIX philosophy, of sections of multiple paradigms of the application layer. It includes example solutions that adhere to the principles listed above. *(Note: It is still being worked on).*
<br><br>

<div align='center'>
  <img src='https://raw.githubusercontent.com/unix-base/home/images/theory__architecture_specificity_diagram.png' width='100%'>
</div>
