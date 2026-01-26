**Linux Architecture**
Application/User-User can give a command using application to computer to execute the output.
Shell- Interactive way to talk to kernal using CLI(command line interface)
Kernel- its computer program where computer understand the Binary(101010) language.which is written in C program
Hardware- Interface between user and computer application.

**The core components of Linux (kernel, user space, init/systemd)**
Kernel- Kernel is core component of linux also called as linux heart
User space- Is the memory area where user applications, system deamons & library runs
init/systemd- init is first process started by kernel it will run untill systems shutdown, PID1

**How processes are created and managed**
Whatever task we give in linux it will create the process with unique process ID also called PID, by default init/systemd process is created
with PID1 and it runs until system get shutdown, this all the processes managed by kernel using unique PID.

**What systemd does and why it matters**
systemd is system and service manager of linux operating system, its first process start by kernel and it will run untill system shutdown,
and systemd by default process id is PID1
