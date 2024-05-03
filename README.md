# Operation Systems Course @ Ariel University

## Lectures:

### Lecture 1

- What is an operating system?
- What is Unix?
- What is Linux?
- What is an open source code?
- Open source license type
- Working in Linux - code coverage, profiles
- Relevant system calls: None
- Relevant chapters in the guide: None
- All the material is in the presentation and only in the presentation
- Relevant chapters in the literature: APUE chapter 1, 2, 3; OSC chapter 1+2

### Lecture 2

Creating processes. Waiting for the processes to finish. signals. Sending a signal to the process. signal processing.

- Relevant system calls:
  - signals:    kill(2), raise(2), signal(2), signal(2)
  - processes:    fork(2) , wait(2), waited(2), execXX
  - Communication between processes using pipe(2)
  - Copying a file descriptor using dup(2) dup2(2)
- Guides: Been guide to IPC chapters 2+3+4 for exercise
- Literature: OSC 3 APUE 7, 19

### Lecture 3

- Relevant system calls: All the system calls that appear in chapters 7.3, 5, 7.2 of the beej manual.
  - socket(2) , setsockopt(2), bind(2), listen(2), accept(2), connect(2), send(2), recv(2), sendto(2), recvfrom(2), close(2)
  - poll(2) select(2)
  - getaddrinfo(2)
- Sources:
  - Lesson 3 Beej guide to network programming chapters 1-3
    Book: APUE 16, CN 5,6
  - Beej guide to network programming chapter 5
    Book: APUE 14, CN 7
  - Beej Guide to network programming 7.3 + 7.2 + 7.1
    APUE 15 book

### Lecture 4

Synchronization models

Communication between processes using locks on files, unix domain sockets, and shared memory using mmap.


- Relevant system calls
  - mmap(2) munmap(2) fcntl(2) socketpair(2) : Calls used to work with Internet sockets (already learned) - to work with unix domain sockets
- Sources:
  - Lesson: Beej guide ot unix IPC chapters 6+10+11
  - Book: OSC 6-8

### Lecture 6

Threads: Threads creation and termination

- Sources:
  - Presentation 
  - Book: OSC 4, APUE 12

### Lecture 7

Synchronization Threads, POSIX Mutex, POSIX cond

- Sources:
  - Presentation
  - Book: OSC 7, APUE 12
 
### Lectire 8

Book: OSC 7, APUE 12


## Copyright Disclaimer

All study materials in this repository for the course "Operation Systems" at Ariel University are the intellectual property of Ariel University.

These materials are provided for non-commercial educational use only. You are free to use, modify, and distribute them, but please attribute Ariel University as the original creator and refrain from using them for commercial purposes without permission.
