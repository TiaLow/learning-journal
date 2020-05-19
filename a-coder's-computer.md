## Text Editors

- Basic editor that comes with your computer. Basic of basic, doesn't do anything extra for you. Must use a plain text editor (no options for bold, underline, etc)
- Third party options like Visual Studio Code that have some additional features like code completion and syntax highlighting. 

**It's important for software developers to be mindful of what text editor to use because ultimately it can make your life writing code easier.**

## Basic Terminal Usage

- Command line interface (cli) instead of graphical user interface (gui "gooey")
- Issuing commands to your computer
- Can have multiple terminals open at once to do different things (cool!)
- Must be a space between the command and first command line argument (or "option")
- Terminal can be found at Applications - Utilities (or command+space and type Terminal)

## Navigation 

- we refer to a file or directory on command line as "path" (a means to get to a particular file or directory on the system) 
  - absolute paths: specify a location in relation to root directory
  - relative paths: specify location in relation to where we currently are in system
- root directory denoted by single backslash and is at the top of the hierarchical structure

### Command Examples

 - pwd (Print Working Directory): tells you what directory you're currently working in
 - ls (list): gives you the listing of what's in your current directory
 - ls -l (list): indicates a long listing
 - ls /etc (list): list our current directory's contents
 - la -a (list): list the contents of directory, including hidden files 
 - cd (change directory):cd [location] to move to another directory
 - file (to figure out file type): file [path]
 
 
 #### Shortcuts
 
 - use up and down arrows to see the history of recent commands used 
 - if you run command cd without any arguments it will always take you back to home directory
 - Tab Completion [link to what this means](https://ryanstutorials.net/linuxtutorial/navigation.php)
 - If you use tab completion before encountering the space in the directory name then the terminal will automatically escape any spaces in the name for you.
 
 ### Other Important Notes
 
 - Everything is a file! (Test file, directory, keyboard, monitor, etc)
 - Under Linux, system ignores file extensions (.gif, .doc, .exe, etc)
   - Linux is *extensionless* system
 - Linux **is** case sensitive
 - Be careful of spaces in file and directory names
   - EX: cd 'Holiday Photos' since without the quotes it is seen as two separate command line arguments. Anything inside quotes is considered single item. 
 - Backslash is an escape character. Putting it before something nullifies the special meaning of the next character. 
 - If a file or directory begins with . then it is hidden. 
 


