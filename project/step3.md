system calls needed: 

open() - to open a file that is used as input or output for a command
fork() - to run a new command in a separate child process
waitpid() - wait for a child process to terminate before continuing 
execvp() - execute the code in the file descriptor specified
pipe() - create a data channel between current process and the process specified as a argument.
close() - close a file descriptor specified
exit() - terminate the current process
dup() - create a copy of the file descriptor specified
chdir() - change to working directory of the current process to the one specified

if (command[first] == exit){
    return exit();
};
if (command[first] == cd){
    return chdir(command[first+1]);
};


String [] currentCommand
currentCommand.
command.getFirststing

check if command is exit(no point in continueing if exit() is called)
check if command is cd (and chdir() to the location specified in the argument that follows)

if input contains command(
    fork current process
    execvp() that command
    set
)
handle internal commands cd and exit

if first command is cd is empty(
    read command from commands
    )
else
    )expression has user input -> run user input

read first string of command.parts
if this string 

Run each command in a separate process, and use a pipe to send the output of one command as input to another command.

