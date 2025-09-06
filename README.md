# Linux & Git Cheat Sheet (IS 601)


Each command below includes a one-line purpose and a simple example.
I created one branch per command and merged each into `main`.files
Purpose: Show the full path of the current directory.
Example: pwd

Purpose: List directory contents.
Example:
    ls -la
Purpose: Move between folders.
Example:
    cd /usr/local
Purpose: Create a new folder.
Example:
    mkdir logs
Purpose: Quickly create a file.
Example:
    touch notes.txt
Purpose: Copy a file or folder.
Example:
   cp notes.txt notes.bak
Purpose: Move or rename files/folders.
Example:
    mv notes.txt docs/notes.txt
Purpose: Move or rename files/folders.
Example:
    mv notes.txt docs/notes.txt

Purpose: Delete files (careful!).
Example:
    rm notes.bak
Purpose: Find lines matching a pattern.
Example:
    grep "ERROR" app.log

Purpose: Adjust read/write/execute bits.
Example:
    chmod +x script.sh

Purpose: Show changes and branch info.
Example:
    git status
Purpose: Add files to the next commit.
Example:
    git add README.md

Purpose: Record staged changes with a message.
Example:
    git commit -m "Add grep example"
Purpose: List/create/delete branches.
Example:
    git branch -a
