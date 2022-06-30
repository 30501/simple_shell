![image](img/simple_shell_header.png)
<h1>Simple Shell</h1>
Release date June 15, 2022

</p>
          </a>
          <a href="https://github.com/30501/simple_shell/commits/master" target="_blank">
               <img alt="commit_activity" src="https://img.shields.io/github/commit-activity/y/Ouyei/simple_shell" />
          </a>
          <a href="https://github.com/30501/simple_shell/graphs/contributors" target="_blank">
               <img alt="contributors" src="https://img.shields.io/github/contributors/Ouyei/simple_shell" />
          </a>
          <a href="https://github.com/30501/simple_shell/blob/master/hsh_shell.c"target="_blank">
               <img alt="code-size" src="https://img.shields.io/tokei/lines/github/Ouyei/simple_shell" />
          </a>
          <a href="https://github.com/30501/simple_shell/blob/master/README.md" target="_blank">
               <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen" />
          </a>
     </p>

## Table of Contents
* [Introduction](#Introduction)
  * What is Shell
  * What is it for
* [Project Information](#Project-Information)
    * Tasks
    * Enviroment
    * General requirements
    * Allowed functions
* [Documentation](#Documentation)
    * Instalation
    * Testing
    * Files
    * Flowchart
* [Authors](#Authors)

## Introduction

### What is Shell
A **shell** is a command-line interpreter, it is the computer program that provides a user interface to access the services of the operating system. Depending on the type of interface they use, shells can be of various types, in this case, a shell program of the type **`sh`** ([Bourne Shell](https://en.wikipedia.org/wiki/Bourne_shell)) will be developed. Users typically interact with a shell using a [terminal emulator](https://en.wikipedia.org/wiki/Terminal_emulator) that is used for entering data into and displaying or printing data from, a computer or a computing system.

### What is it for
This consists of interpreting orders. It incorporates features such as process control, input/output redirection, law listing and reading, protection, communications, and a command language for writing batch programs or scripts. All Unix-type systems have at least one interpreter compatible with the Bourne shell. The Bourne shell program is found within the Unix file hierarchy at **`/bin/sh`**.

## Project Information

### Tasks

* Task 0. README, man_1_simple_shell, AUTHORS
* Task 1. Betty would be proud
* Task 2. Simple shell 0.1
* Task 3. Simple shell 0.2
* Task 4. Simple shell 0.3
* Task 5. Simple shell 0.4
* Task 6. Simple shell 1.0
* Task 7. What happens when you type ls -l in the shell

### Enviroment

<!-- ubuntu -->
<a href="https://ubuntu.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Ubuntu&color=E95420&logo=Ubuntu&logoColor=E95420&labelColor=2F333A" alt="Suite CRM"></a> OS: Ubuntu 20.04 LTS
<!-- bash -->
<a href="https://www.gnu.org/software/bash/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GNU%20Bash&color=4EAA25&logo=GNU%20Bash&logoColor=4EAA25&labelColor=2F333A" alt="terminal"></a>
<!-- c -->	
<a href="https://www.cprogramming.com/" target="_blank"><img src="https://img.shields.io/static/v1?label=&message=C%20Language&color=5C6BC0&logo=c&logoColor=A8B9CC&labelColor=2F333A" alt="C Low level programming language"></a> Language: C
Compiler: gcc 9.3.0
<!-- vim -->
<a href="https://www.vim.org/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Vim&color=019733&logo=Vim&logoColor=019733&labelColor=2F333A" alt="Suite CRM"></a> Editor: VIM 8.1.2269
<!-- git -->
<a href="https://git-scm.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Git&color=F05032&logo=Git&logoColor=F05032&labelColor=2F333A" alt="git distributed version control system"></a> Control version: Git
<!-- github -->
<a href="https://github.com" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GitHub&color=181717&logo=GitHub&logoColor=f2f2f2&labelColor=2F333A" alt="Github"></a>

Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)

### General requirements
 * Allowed editors: vi, vim, emacs
 * All your files will be compiled on `Ubuntu 14.04 LTS`
 * Your C programs and functions will be compiled with `gcc 4.8.4` using the flags `-Wall` `-Werror` `-Wextra` and `-pedantic`
 * Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
 * No more than 5 functions per file
 * All your header files should be include guarded
 * This shell should not have any memory leaks
 * Unless specified otherwise, your program must have the exact same output as `sh` (`/bin/sh`) as well as the exact same error output.

### Allowed functions used 

* `execve` (man 2 execve)
* `exit` (man 3 exit)
* `_exit` (man 2 _exit)
* `fork` (man 2 fork)
* `free` (man 3 free)
* `getline` (man 3 getline)
* `isatty` (man 3 isatty)
* `malloc` (man 3 malloc)
* `perror`(man 3 perror)
* `signal` (man 2 signal)
* `stat` (__ xstat) (man 2 stat)
* `strtok` (man 3 strtok)
* `wait` (man 2 wait)
* `write` (man 2 write)

## Documentation

### Installation

- Clone this repository: `git clone "https://github.com/Ouyei/simple_shell"`
- Change directories into the repository: `cd simple_shell`
- Compile: `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
- Run the shell in interactive mode: `./hsh`
- Or run the shell in non-interactive mode: example `echo "Hello world!" | ./hsh`

### Testing

First compile and then run the executable file on your terminal
For compile see [Installation](#installation) section

```
$ ./hsh
$
$ ls -l
total 33
-rw-r--r-- 1 root root  238 Dec  6 08:34 AUTHORS
-rwxr-xr-x 1 user user 3036 Jun 29 18:02 aux_error1.c
-rwxr-xr-x 1 user user 1518 Jun 29 18:02 aux_error2.c
-rw-r--r-- 1 user user 1040 Jun 29 18:02 aux_help2.c
-rw-r--r-- 1 user user 2412 Jun 29 18:02 aux_help.c
-rw-r--r-- 1 user user  958 Jun 29 18:02 aux_lists2.c
-rw-r--r-- 1 user user 1706 Jun 29 18:02 aux_lists.c
-rw-r--r-- 1 user user 1942 Jun 29 18:02 aux_mem.c
-rw-r--r-- 1 user user 1369 Jun 29 18:02 aux_stdlib.c
-rw-r--r-- 1 user user 2207 Jun 29 18:02 aux_str2.c
-rw-r--r-- 1 user user  420 Jun 29 18:02 aux_str3.c
-rw-r--r-- 1 user user 1777 Jun 29 18:02 aux_str.c
-rw-r--r-- 1 user user 2766 Jun 29 18:02 cd.c
-rw-r--r-- 1 user user  642 Jun 29 18:02 cd_shell.c
-rw-r--r-- 1 user user 3283 Jun 29 18:02 check_syntax_error.c
-rw-r--r-- 1 user user 3442 Jun 29 18:02 cmd_exec.c
-rw-r--r-- 1 user user 1403 Jun 29 18:02 env1.c
-rw-r--r-- 1 user user 2490 Jun 29 18:02 env2.c
-rw-r--r-- 1 user user  373 Jun 29 18:02 exec_line.c
-rw-r--r-- 1 user user  605 Jun 29 18:02 exit_shell.c
-rw-r--r-- 1 user user  519 Jun 29 18:02 get_builtin.c
-rwxr-xr-x 1 user user  736 Jun 29 18:02 get_error.c
-rw-r--r-- 1 user user  842 Jun 29 18:02 get_help.c
-rw-r--r-- 1 user user 1425 Jun 29 18:02 get_line.c
-rw-r--r-- 1 user user  179 Jun 29 18:02 get_sigint.c
-rw-r--r-- 1 user user   65 Aug 28  2019 .gitignore
-rw-r--r-- 1 user user 1160 Jun 29 18:29 main.c
-rw-r--r-- 1 user user 5793 Jun 29 18:02 main.h
-rw-r--r-- 1 user user 5566 Aug 28  2019 man_1_simple_shell
-rw-r--r-- 1 user user  274 Jun 29 18:02 read_line.c
-rw-r--r-- 1 user user 7845 Jun 29 18:02 README.md
-rw-r--r-- 1 user user 3297 Jun 29 18:02 rep_var.c
-rw-r--r-- 1 user user 1147 Jun 29 18:02 shell_loop.c
-rw-r--r-- 1 user user 3684 Jun 29 18:02 split.c
```
### Files

|File|Description|
|---|---|
|[AUTHORS](https://github.com/30501/simple_shell/blob/master/AUTHORS)|Contributors in this repository|
|[README.md](https://github.com/30501/simple_shell/blob/master/README.md)|Information about our repository|

## Authors

<li> Bethelhem hunegnaw - <a href="https://github.com/30501">30501</a></li>
<li> Surafel Abera - <a href="https://github.com/Grey-Surafel-Abera">Grey-Surafel-Abera</a></li>

