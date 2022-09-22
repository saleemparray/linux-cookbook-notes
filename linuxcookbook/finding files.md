
## Finding All Files That Match a Pattern

• To find all the files on the system that have the text `audio' anywhere in their name, type:

    $ locate audio RET

• To find all the files on the system whose file names end with the text `ogg', type:

    $ locate *ogg RET

• To find all hidden "dotfiles" on the system, type:

    $ locate /. RET


NOTE:locate searches are not case sensitive.


### Finding the Largest Files in a Directory


• To list the files in the current directory, with their attributes, sorted with the largest files first, type:

    $ ls −lS RET

### Finding the Smallest Files in a Directory

• To list the files in the current directory and their attributes, sorted from smallest to largest, type:

    $ ls −lSr RET
