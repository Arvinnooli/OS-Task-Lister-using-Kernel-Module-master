# OS-Task-Lister-using-Kernel-Module-ubuntu
An Assignment project made as a part of the Operating at PES University. The objective of the project was to demonstrate a kernel module that lists all current tasks in a Linux system

## Installation
```
$ git clone https://github.com/Arvinnooli/OS-Task-Lister-using-Kernel-Module-master.git
$ cd OS-Task-Lister-using-Kernel-Module-master/
```

## How to use
```
$ cd src/[linear|dfs]
$ make                                  # Make module
$ insmod tasks_lister_[linear|dfs].ko   # Install module
$ dmesg                                 # Show message
$ rmmod tasks_lister_[linear|dfs]       # Remove module
$ dmesg                                 # Show message
$ dmesg -C                              # Clear message
```

