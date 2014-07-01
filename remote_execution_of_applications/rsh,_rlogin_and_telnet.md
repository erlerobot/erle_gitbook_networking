## Rsh, rlogin and telnet

The `rlogin` and `rsh` commands for remote login and remote execution of commands are inherited from UNIX. While seldom used because they are blatantly insecure, they still come with almost every Linux distribution for backward compatibility with UNIX programs.

Telnet, on the other hand, is still commonly used, often by system and network administrators. Telnet is one of the most powerful tools for remote access to files and remote administration, allowing connections from anywhere on the Internet. Combined with an X server, remote graphical applications can be displayed locally. There is no difference between working on the local machine and using the remote machine.

Because the entire connection is unencrypted, allowing telnet connections involves taking high security risks. For normal remote execution of programs, Secure SHell or `ssh` is advised. We will discuss the secure method later in this section.

However, `telnet` is still used in many cases.
For more information use man telnet, and for installing them visit this website http://www.cyberciti.biz/faq/how-do-i-turn-on-telnet-service-on-for-a-linuxfreebsd-system/




