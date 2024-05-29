# Weenix

A semester-long project taken as part of CS2670 (Graduate Operating Systems) where I developed my own operating system kernel based on Unix. You can find more information about the course [here](https://brown-cs1690.github.io/brown-cs167-s24/) and the project [here](https://github.com/brown-cs1690/handout/wiki).

This was split into 5 sub-projects which are ordered in terms of completion below:

- <b>Procs</b>: The basic building blocks of the OS, containing implementation of threads, processes, and synchronization primitives
- <b>Drivers</b>: Device drivers for terminals, disks, and the memory devices `/dev/zero` and `/dev/null`
- <b>VFS (Virtual File System) </b>: Implementation of a common interface between the operating system kernel and the various file systems such as RAMFS, S5FS and device drivers

- <b> S5FS (System V File System) </b>: Implementation of on-disk file system based on original Unix file system
- <b> VM (Virtual Memory) </b>: Management of user address spaces, running user-level code, and servicing system calls. This project essentially combined all of the previous components into a fully functional operating system. Additionall functionalities include virtual memory management, page fault handling, memory management with anonymous and shadow objects, and system calls (such as `fork`, `brk` and `mmap` calls)

Note: To respect Brown's academic code, this is a placeholder repo. If you are a potential employer and would like access to the code, please contact me at `aryan_singh@brown.edu`
