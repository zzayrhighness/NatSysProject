# Net&Sys Assignment: Running Containers for Application Development

Group Name: buttercup

Team Mates:
1. Izza Zulaikha binti Mohd Fauzi (2216502)
2. Iris Mahirah binti Mohammad Fadhli (2219366)
3. Mashitah binti Nordin (2111110)

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository.  
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** 
https://github.com/zzayrhighness/NatSysProject
2. How many files and folders are in this repository. ***(1 mark)*** 
4


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** 
Ubuntu.
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 
4 cores, 8 GB RAM, 32 GB SSD
3. Why must we commit and sync our current work on source control? ***(1 mark)*** 
We must commit and sync our current work on source control because if we don't, our work will be lost since it is not saved into the main repository. Committing and syncing our changes ensures that our work is uploaded to the GitHub repository, making it persistent and accessible even after we close the codespace.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```

@zzayrhighness ➜ /workspaces/NatSysProject (main) $ whoami
codespace

***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ pwd
/workspaces/NatSysProject

2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin

3. Run the command **df** . ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10409368  20744212  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        0     65536   0% /dev/shm
/dev/root       30298176 24307732   5974060  81% /vscode
/dev/sda1       46127956      108  43752272   1% /tmp
/dev/loop3      32847680 10409368  20744212  34% /workspaces

4. Run the command **du** . ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ du
4       ./.git/branches
8       ./.git/objects/1b
8       ./.git/objects/83
8       ./.git/objects/47
8       ./.git/objects/71
12      ./.git/objects/62
8       ./.git/objects/58
12      ./.git/objects/73
8       ./.git/objects/a6
8       ./.git/objects/04
8       ./.git/objects/fd
12      ./.git/objects/e5
8       ./.git/objects/41
8       ./.git/objects/7b
8       ./.git/objects/24
8       ./.git/objects/c6
12      ./.git/objects/3d
8       ./.git/objects/0b
12      ./.git/objects/72
12      ./.git/objects/d2
8       ./.git/objects/86 
12      ./.git/objects/1c
8       ./.git/objects/eb
8       ./.git/objects/ab
12      ./.git/objects/ff
12      ./.git/objects/af
8       ./.git/objects/74
8       ./.git/objects/96
12      ./.git/objects/70
8       ./.git/objects/d8
8       ./.git/objects/91
8       ./.git/objects/c3
8       ./.git/objects/3a
12      ./.git/objects/17
12      ./.git/objects/2e
8       ./.git/objects/0d
8       ./.git/objects/52
8       ./.git/objects/fc
8       ./.git/objects/e7
16      ./.git/objects/fb
8       ./.git/objects/fa
8       ./.git/objects/4b
12      ./.git/objects/6e
12      ./.git/objects/b5
8       ./.git/objects/49
8       ./.git/objects/60
8       ./.git/objects/fe
8       ./.git/objects/20
8       ./.git/objects/f6
8       ./.git/objects/3f
8       ./.git/objects/a3
8       ./.git/objects/cd
8       ./.git/objects/f2
8       ./.git/objects/b2
8       ./.git/objects/93
8       ./.git/objects/81
8       ./.git/objects/e9
8       ./.git/objects/cb
12      ./.git/objects/64
8       ./.git/objects/b9
8       ./.git/objects/b6
8       ./.git/objects/4f
8       ./.git/objects/4a
4       ./.git/objects/info
12      ./.git/objects/14
1824    ./.git/objects/pack
12      ./.git/objects/44
2420    ./.git/objects
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
68      ./.git/hooks
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/refs/tags
8       ./.git/refs/heads
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
28      ./.git/refs
8       ./.git/info
2596    ./.git
1972    ./images
4588    .

5. Run the command **ls** . ***(1 mark)***
zzayrhighness ➜ /workspaces/NatSysProject (main) $ ls
README.md  images

6. Run the command **ls -asl** . ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ ls -asl
total 36
 4 drwxrwxrwx+ 4 codespace root  4096 Jun 17 17:47 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jun 17 17:47 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jun 17 17:47 .git
20 -rw-rw-rw-  1 codespace root 16922 Jun 18 16:27 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jun 17 17:47 images

7. Run the command **free -h** . ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.4Gi       211Mi        64Mi       6.1Gi       6.0Gi
Swap:            0B          0B          0B
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.973
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2983.556
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

9. Run the command **top** and type **q** to quit. ***(1 mark)*** 
top - 16:30:40 up 28 min,  0 users,  load average: 0.08, 0.25, 0.26
Tasks:  20 total,   1 running,  19 sleeping,   0 stopped,   0 zombie
%Cpu(s):  4.6 us,  4.3 sy,  0.0 ni, 90.8 id,  0.0 wa,  0.0 hi,  0.3 si,  0.0 st
MiB Mem :   7929.6 total,    244.8 free,   1410.5 used,   6274.3 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6139.4 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                 
    575 codespa+  20   0   21.5g 380052  49920 S   1.3   4.7   0:26.91 node                                                                                    
    555 codespa+  20   0 1326188  99704  45184 S   0.7   1.2   0:04.25 node                                                                                    
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.05 docker-init                                                                             
      7 codespa+  20   0    7236   1664   1664 S   0.0   0.0   0:00.02 sleep  

10. Run the command **uname -a**. ***(1 mark)*** 
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ uname -a
Linux codespaces-705dee 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux

11. What is the available free memory in the system. ***(1 mark)*** 
6.0 GiB

12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
20,744,212 KB (20.7 GB)

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
The Linux version 6.5.0-1021-azure and the hardware architecture is x86_64

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
ls: Shows the names of files and directories in the current folder.
ls -asl: Displays detailed information, including hidden files, permissions, number of links, owner, group, size, and last modified date.

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 
 2560 4K pages

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 
3243.973 MHz

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
node with PID 575, using 1.3% of the CPU

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker pull debian
Using default tag: latest
doclatest: Pulling from library/debian
Digest: sha256:a92ed51e0996d8e9de041ca05ce623d2c491444df6a535a566dabd5cb8336946
Status: Image is up to date for debian:latest
docker.io/library/debian:latest
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker run --detach -it debian
a776bd2bbce24536843da28904c32953ac1f58510d7f5cec0a6d441f8ea9548d

2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
a776bd2bbce2   debian    "bash"    21 seconds ago   Up 20 seconds             hardcore_carver
7a453b6f2e3a   debian    "bash"    47 minutes ago   Up 47 minutes             hopeful_wozniak
866b991a8ffe   debian    "bash"    49 minutes ago   Up 49 minutes             recursing_herschel

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker exec -i -t hardcore_carver /bin/bash

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```
root@a776bd2bbce2:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (29.0 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...
root@a776bd2bbce2:/# cd /root
root@a776bd2bbce2:~# nano helloworld.text


5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson
34
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker stop hardcore_carver
hardcore_carver
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
a776bd2bbce2   debian    "bash"    4 minutes ago    Exited (137) 17 seconds ago             hardcore_carver
7a453b6f2e3a   debian    "bash"    52 minutes ago   Up 52 minutes                           hopeful_wozniak
866b991a8ffe   debian    "bash"    53 minutes ago   Up 53 minutes                           recursing_herschel
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker restart hardcore_carver
hardcore_carver

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker stop hardcore_carver
hardcore_carver
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker ps -a 
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                       PORTS     NAMES
a776bd2bbce2   debian    "bash"    5 minutes ago    Exited (137) 8 seconds ago             hardcore_carver
7a453b6f2e3a   debian    "bash"    53 minutes ago   Up 53 minutes                          hopeful_wozniak
866b991a8ffe   debian    "bash"    54 minutes ago   Up 54 minutes                          recursing_herschel
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ docker rm hardcover_carver
Error response from daemon: No such container: hardcover_carver

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** 
No, by default, files within the container are not permanent. Since containers are meant to be ephemeral, any modifications made to the file system will be erased upon stopping or removing the container. To keep data outside of the container's filesystem, volumes or bind mounts can be used to achieve persistence.

2. Can we run two, or three instances of debian linux? . ***(1 mark)*** 
Yes, we are able to operate many Debian Linux instances at once. Since each instance operates in a separate, isolated container, numerous containers can operate independently of one another without interfering with one another.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ mkdir myroot
@zzayrhighness ➜ /workspaces/NatSysProject (main) $ cd myroot/
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ pwd
/workspaces/NatSysProject/myroot
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker run --detach -it -v /workspaces/NatSysProject/myroot:/root debian
2e544a2b9d5e53ce884a38b83d71ecc330d9b358dd1e65025acaa64481905e49

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** 

user and group : root 
This is because the container runs with root privileges unless otherwise specified

@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
007e79191084   debian    "bash"    6 seconds ago    Up 6 seconds              awesome_driscoll
2e544a2b9d5e   debian    "bash"    20 minutes ago   Up 20 minutes             pedantic_austin
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker exec -it 007e79191084 /bin/bash
root@007e79191084:/# echo "Hello, World!" > /root/helloworld.txt
root@007e79191084:/# exit
exit
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ ls -l /workspaces/NatSysProject/myroot
total 4
-rw-rw-rw- 1 root root 14 Jun 19 13:58 helloworld.txt

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
Yes, changeable 

@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ sudo chown -R codespace:codespace /workspaces/NatSysProject/myroot
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ ls -l /workspaces/NatSysProject/myroot
total 4
-rw-rw-rw- 1 codespace codespace 14 Jun 19 13:58 helloworld.txt

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine

2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)***

Permission : drwxrwxrwx+
user and group : root 
@zzayrhighness ➜ /workspaces/NatSysProject/webpage (main) $ docker exec -it awesome_driscoll /bin/bash
root@e8dbaebf3bda:/usr/local/apache2# ls -ld /usr/local/apache2/htdocs
drwxrwxrwx+ 2 1000 1000 4096 Jun 19 06:19 /usr/local/apache2/htdocs

2. What port is the apache web server running. ***(1 mark)***
apache web server port: 80 

@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker ps
CONTAINER ID   IMAGE     COMMAND              CREATED          STATUS          PORTS                                   NAMES
d338564ff037   httpd     "httpd-foreground"   13 seconds ago   Up 12 seconds   0.0.0.0:8080->80/tcp, :::8080->80/tcp   exciting_bassi
007e79191084   debian    "bash"               6 minutes ago    Up 6 minutes                                            awesome_driscoll
2e544a2b9d5e   debian    "bash"               27 minutes ago   Up 27 minutes                                           pedantic_austin

3. What port is open for http protocol on the host machine? ***(1 mark)***
Host Machine HTTP Port : 8080

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** 
BusyBox is a lightweight, multi-tool executable that combines many common Unix utilities into a single executable file. The --name command switch is used to specify the name of the BusyBox executable.


2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
3cd062900245   bridge    bridge    local
fa77161499e8   host      host      local
92e4071ff96b   none      null      local

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***

@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker inspect c1
[
    {
        "Id": "3a65d5e5e34d664c47d0e8151474db8e33821d5642f3186e42eaa8b5de95dcb2",
        "Created": "2024-06-19T14:56:37.667163426Z",
        "Path": "sleep",
        "Args": [
            "3600"
        ],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 69007,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-06-19T14:56:38.293248851Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/3a65d5e5e34d664c47d0e8151474db8e33821d5642f3186e42eaa8b5de95dcb2/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/3a65d5e5e34d664c47d0e8151474db8e33821d5642f3186e42eaa8b5de95dcb2/hostname",
        "HostsPath": "/var/lib/docker/containers/3a65d5e5e34d664c47d0e8151474db8e33821d5642f3186e42eaa8b5de95dcb2/hosts",
        "LogPath": "/var/lib/docker/containers/3a65d5e5e34d664c47d0e8151474db8e33821d5642f3186e42eaa8b5de95dcb2/3a65d5e5e34d664c47d0e8151474db8e33821d5642f3186e42eaa8b5de95dcb2-json.log",
        "Name": "/c1",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "bluenet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                11,
                95
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/ec861901b6c10539fc207d7ba26751ead169ce0bbc808e30e2f4bdbc9dcdb18c-init/diff:/var/lib/docker/overlay2/34427e10d6720117eb065696e2fdb25635bca024de40bed7039f34aa0c28ac0e/diff",
                "MergedDir": "/var/lib/docker/overlay2/ec861901b6c10539fc207d7ba26751ead169ce0bbc808e30e2f4bdbc9dcdb18c/merged",
                "UpperDir": "/var/lib/docker/overlay2/ec861901b6c10539fc207d7ba26751ead169ce0bbc808e30e2f4bdbc9dcdb18c/diff",
                "WorkDir": "/var/lib/docker/overlay2/ec861901b6c10539fc207d7ba26751ead169ce0bbc808e30e2f4bdbc9dcdb18c/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "3a65d5e5e34d",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sleep",
                "3600"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "bf38df7e250c3d380b8ebd672008fbe748cc5f256c82b3a3f8ebe526b63864c2",
            "SandboxKey": "/var/run/docker/netns/bf38df7e250c",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "bluenet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:12:00:02",
                    "NetworkID": "da311ead556beb4d19401cc1fe13b6b4f191d8c339e0103b41ecd32b1335ad48",
                    "EndpointID": "de4e89b86a2d136d5f25e36f2b08ffaf34a1b839cf4bdc06f05ae48e0acf67a8",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c1",
                        "3a65d5e5e34d"
                    ]
                }
            }
        }
    }
]
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker inspect c2
[
    {
        "Id": "79411ddaf9ec0dc307bd545e41e57d8e2f8958ed40bab840a132ad394fc2b1dd",
        "Created": "2024-06-19T14:56:38.375407473Z",
        "Path": "sleep",
        "Args": [
            "3600"
        ],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 69106,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-06-19T14:56:38.951130807Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/79411ddaf9ec0dc307bd545e41e57d8e2f8958ed40bab840a132ad394fc2b1dd/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/79411ddaf9ec0dc307bd545e41e57d8e2f8958ed40bab840a132ad394fc2b1dd/hostname",
        "HostsPath": "/var/lib/docker/containers/79411ddaf9ec0dc307bd545e41e57d8e2f8958ed40bab840a132ad394fc2b1dd/hosts",
        "LogPath": "/var/lib/docker/containers/79411ddaf9ec0dc307bd545e41e57d8e2f8958ed40bab840a132ad394fc2b1dd/79411ddaf9ec0dc307bd545e41e57d8e2f8958ed40bab840a132ad394fc2b1dd-json.log",
        "Name": "/c2",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "rednet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                11,
                95
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/759cee06c9162c98095565b5bfd42f80f9e74d887553ff20b987aebc09f5648e-init/diff:/var/lib/docker/overlay2/34427e10d6720117eb065696e2fdb25635bca024de40bed7039f34aa0c28ac0e/diff",
                "MergedDir": "/var/lib/docker/overlay2/759cee06c9162c98095565b5bfd42f80f9e74d887553ff20b987aebc09f5648e/merged",
                "UpperDir": "/var/lib/docker/overlay2/759cee06c9162c98095565b5bfd42f80f9e74d887553ff20b987aebc09f5648e/diff",
                "WorkDir": "/var/lib/docker/overlay2/759cee06c9162c98095565b5bfd42f80f9e74d887553ff20b987aebc09f5648e/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "79411ddaf9ec",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sleep",
                "3600"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "fccab2876a60249b04c79aaf764b4f33915cd4f7c2cbfc59d8807e55e7b32846",
            "SandboxKey": "/var/run/docker/netns/fccab2876a60",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "rednet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:13:00:02",
                    "NetworkID": "449e75b874a624e7083f06761f5610ebfac0de8dbc652908d0eae0e61af314eb",
                    "EndpointID": "117d479a47735b066bf64d8df85f90e0bd7f19b6ebe120875d631d592c57cca0",
                    "Gateway": "172.19.0.1",
                    "IPAddress": "172.19.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c2",
                        "79411ddaf9ec"
                    ]
                }
            }
        }
    }
]


4. What is the network address for the running container c1 and c2.
IPAddress bluenet : 172.18.0.2
IPAddress rednet : 172.19.0.2

5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***

@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker exec c1 ping c2
ping: bad address 'c2'

No cannot because they are in separate Docker networks

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker network create bridgenet
nect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c28528afbc76303934c7d82209a840fe1cd9e5649e6b3cca40306ab2a8535e31c9
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker network connect bridgenet c1
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker network connect bridgenet c2
@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker exec c1 ping c2

@zzayrhighness ➜ /workspaces/NatSysProject/myroot (main) $ docker exec c1 ping c2
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.141 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.081 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.091 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.066 ms
64 bytes from 172.20.0.3: seq=6 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=7 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=8 ttl=64 time=0.064 ms
64 bytes from 172.20.0.3: seq=9 ttl=64 time=0.067 ms
64 bytes from 172.20.0.3: seq=10 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=11 ttl=64 time=0.065 ms
64 bytes from 172.20.0.3: seq=12 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=13 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=14 ttl=64 time=0.098 ms
64 bytes from 172.20.0.3: seq=15 ttl=64 time=0.085 ms
64 bytes from 172.20.0.3: seq=16 ttl=64 time=0.091 ms
64 bytes from 172.20.0.3: seq=17 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=18 ttl=64 time=0.104 ms
64 bytes from 172.20.0.3: seq=19 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=20 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=21 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=22 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=23 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=24 ttl=64 time=0.098 ms
64 bytes from 172.20.0.3: seq=25 ttl=64 time=0.066 ms
64 bytes from 172.20.0.3: seq=26 ttl=64 time=0.084 ms
64 bytes from 172.20.0.3: seq=27 ttl=64 time=0.064 ms
64 bytes from 172.20.0.3: seq=28 ttl=64 time=0.096 ms
64 bytes from 172.20.0.3: seq=29 ttl=64 time=0.067 ms
64 bytes from 172.20.0.3: seq=30 ttl=64 time=0.100 ms
64 bytes from 172.20.0.3: seq=31 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=32 ttl=64 time=0.082 ms
64 bytes from 172.20.0.3: seq=33 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=34 ttl=64 time=0.101 ms
64 bytes from 172.20.0.3: seq=35 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=36 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=37 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=38 ttl=64 time=0.081 ms
64 bytes from 172.20.0.3: seq=39 ttl=64 time=0.084 ms
64 bytes from 172.20.0.3: seq=40 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=41 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=42 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=43 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=44 ttl=64 time=0.116 ms
64 bytes from 172.20.0.3: seq=45 ttl=64 time=0.091 ms
64 bytes from 172.20.0.3: seq=46 ttl=64 time=0.127 ms
64 bytes from 172.20.0.3: seq=47 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=48 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=49 ttl=64 time=0.081 ms
64 bytes from 172.20.0.3: seq=50 ttl=64 time=0.106 ms
64 bytes from 172.20.0.3: seq=51 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=52 ttl=64 time=0.071 ms
64 bytes from 172.20.0.3: seq=53 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=54 ttl=64 time=0.097 ms
64 bytes from 172.20.0.3: seq=55 ttl=64 time=0.084 ms
64 bytes from 172.20.0.3: seq=56 ttl=64 time=0.092 ms
64 bytes from 172.20.0.3: seq=57 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=58 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=59 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=60 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=61 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=62 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=63 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=64 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=65 ttl=64 time=0.084 ms
64 bytes from 172.20.0.3: seq=66 ttl=64 time=0.105 ms
64 bytes from 172.20.0.3: seq=67 ttl=64 time=0.068 ms
64 bytes from 172.20.0.3: seq=68 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=69 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=70 ttl=64 time=0.111 ms
64 bytes from 172.20.0.3: seq=71 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=72 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=73 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=74 ttl=64 time=0.103 ms
64 bytes from 172.20.0.3: seq=75 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=76 ttl=64 time=0.104 ms
64 bytes from 172.20.0.3: seq=77 ttl=64 time=0.067 ms
64 bytes from 172.20.0.3: seq=78 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=79 ttl=64 time=0.088 ms
64 bytes from 172.20.0.3: seq=80 ttl=64 time=0.102 ms
64 bytes from 172.20.0.3: seq=81 ttl=64 time=0.114 ms
64 bytes from 172.20.0.3: seq=82 ttl=64 time=0.106 ms
64 bytes from 172.20.0.3: seq=83 ttl=64 time=0.086 ms
64 bytes from 172.20.0.3: seq=84 ttl=64 time=0.091 ms
64 bytes from 172.20.0.3: seq=85 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=86 ttl=64 time=0.093 ms
64 bytes from 172.20.0.3: seq=87 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=88 ttl=64 time=0.104 ms
64 bytes from 172.20.0.3: seq=89 ttl=64 time=0.091 ms
64 bytes from 172.20.0.3: seq=90 ttl=64 time=0.100 ms
64 bytes from 172.20.0.3: seq=91 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=92 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=93 ttl=64 time=0.081 ms
64 bytes from 172.20.0.3: seq=94 ttl=64 time=0.104 ms
64 bytes from 172.20.0.3: seq=95 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=96 ttl=64 time=0.096 ms
64 bytes from 172.20.0.3: seq=97 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=98 ttl=64 time=0.094 ms
64 bytes from 172.20.0.3: seq=99 ttl=64 time=0.085 ms
64 bytes from 172.20.0.3: seq=100 ttl=64 time=0.099 ms

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
