#SSH Mount
Mounts a directory with remote directories and files from an SSH connection ultilizando sshfs, and opens a terminal in connection with standard ssh.

##install

```shell
$ git clone https://github.com/PhilippeAssis/sshmount.git
$ cd sshmount
$ sudo chmod +x install
$ ./install
```
or
```shell
$ git clone https://github.com/PhilippeAssis/sshmount.git && cd sshmount && sudo chmod +x install && ./install
```

##Usage

Starting an SSH connection to the transmission terminal

```shell
$ sshmount <user>@<server> <serverDirectory> -p <password> -t
```

"-t" starts an ssh connection on the terminal

Starting a simple connection
```shell
$ sshmount <server> <user>
```
or
```shell
$ sshmount <user>@<server>
```

##Help
Use -h for instructions
```shell
$ sshmount -h
```
