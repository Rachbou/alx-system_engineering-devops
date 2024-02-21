##Command line for the win##

**steps you followed to use the SFTP command-line tool

* connect to the SFTP :
Command : sftp <Username>@<Host>
with :
	<Host> : Your host from the sandbox environment.
	<Username> : Your Username from the sandbox environment.

* you will be asked for the Password. type the Password from the sandbox environment.

* After connection, browser to your directories localy and remotely
Command 1 : cd /root/alx-system_engineering-devops/command_line_for_the_win/
Command 2 : lcd {...}/command_line_for_the_win/
with :
	{...} : is the path to your local directory.

*then you can transfer the files you want between directories
Command : put *
this command transfers all the files in your local directory {command_line_for_the_win} to the remote directory {alx-system_engineering-devops/command_line_for_the_win} on the sandbox

*Now you can exit the SFTP
Command : exit
