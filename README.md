# cmd
Cmd.exe
# What is cmd.exe?
cmd.exe is the default command-line interpreter for the OS/2,[1] eComStation, ArcaOS, Microsoft Windows (Windows NT family and Windows CE family), and ReactOS[2] operating systems. The name refers to its executable filename. It is also commonly referred to as cmd or the Command Prompt, referring to the default window title on Windows. The implementations differ on the various systems but the behavior and basic set of commands is generally consistent. cmd.exe is the counterpart of COMMAND.COM in DOS and Windows 9x systems, and analogous to the Unix shells used on Unix-like systems. The initial version of cmd.exe for Windows NT was developed by Therese Stowell.[3] Windows CE 2.11 was the first embedded Windows release to support a console and a Windows CE version of cmd.exe.[4] On Windows CE .NET 4.2,[5] Windows CE 5.0[6] and Windows Embedded CE 6.0[7] it is also referred to as Command Processor Shell. The ReactOS implementation of cmd.exe is derived from FreeCOM, the FreeDOS command line interpreter.[2]
# Operation
cmd.exe interacts with the user through a command-line interface. On Windows, this interface is implemented through the Win32 console. cmd.exe may take advantage of features available to native programs of its own platform. For example, on OS/2 and Windows, it can use real pipes in command pipelines, allowing both sides of the pipeline to run concurrently. As a result, it is possible to redirect the standard error stream. (COMMAND.COM uses temporary files, and runs the two sides serially, one after the other.)

Multiple commands can be processed in a single command line using the command separator &&.[8] For example:

C:\>CommandA && CommandB && CommandC
On Windows XP or later, the maximum length of the string that can be used at the command prompt is 8191 characters. On earlier versions, such as Windows 2000 or Windows NT 4.0, the maximum length of the string is 2047 characters. This limit includes the command line, individual environment variables that are inherited by other processes, and all environment variable expansions.[9]

Quotation marks are required for the following special characters:[8]

& < > [ ] { } ^ = ; ! ' + , ` ~ [white space]
