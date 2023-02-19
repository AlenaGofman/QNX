## QNX
An example of the program in the QNX system

The *QNX RTOS* is a **real-time system**, it is a *Posix* compatible *UNIX* system that must respond to events in an environment external to the system or act on the environment within the required time constraints. The *RTOS* system cares about the time it takes to get a result. It's not a clone or distribution, it's a standalone *UNIX*-like real-time operating system. Used in industry and process automation for specific equipment. It is also interesting because in it you can not only program, but also:
- create *QNX* boot images in a *VMware* virtual system,
- when creating a project, you can select the *process architecture* (*ARM, MIPS, PPC, SH, X86*) for the generated binary file, as well as the compilation option: include or not information for the debugger,

![QNX](https://user-images.githubusercontent.com/15179165/219965307-86ce1e1e-4ef5-4a3c-83d8-2761d01faf38.png)

- test programs using the code coverage metric *Code Coverage*

![QNX](https://user-images.githubusercontent.com/15179165/219965354-ed39efed-0aa7-444b-a982-78ca7243d7a3.png)

- debug applications built with a static (dynamic) library using *breakpoints*,
- analyze the work of processes (threads) using the *procnto-instr* tracing module,

![QNX](https://user-images.githubusercontent.com/15179165/219965393-538fcfda-791f-46fe-8dca-c3e0f0f3d634.png)

- profile applications using *Application Profiler*,
- profile applications with *System Profiler*,

![QNX](https://user-images.githubusercontent.com/15179165/219965426-a7ba8a9e-5324-415f-8173-1f38f5c37575.png)

- analyze the search for errors in *dump* files.

#### The following video shows an example of creating a thread when transferring server data to a client, the example expands the concepts of creating a thread and allows you to use it when transferring multi-threaded information:

![QNX](https://user-images.githubusercontent.com/15179165/219965186-38966945-d2ad-4362-936e-48f7cc9e31a6.mp4)
