


# Proveedor: AWS

## IP's:

54.175.70.189	ec2-54-175-70-189.compute-1.amazonaws.com
10.1.2.207 ip-10-1-2-207.ec2.internal

52.207.229.178 ec2-52-207-229-178.compute-1.amazonaws.com
10.1.2.246 ip-10-1-2-246.ec2.internal

34.230.7.202 ec2-34-230-7-202.compute-1.amazonaws.com
10.1.2.166 ip-10-1-2-166.ec2.internal

54.236.121.242 ec2-54-236-121-242.compute-1.amazonaws.com
10.1.2.172	ip-10-1-2-172.ec2.internal

# SO
Oracle 7.4

# Listar la capacidad 
## IP: 10.1.2.207 
```
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvda1       50G  822M   50G   2% /
devtmpfs         15G     0   15G   0% /dev
tmpfs            15G     0   15G   0% /dev/shm
tmpfs            15G   17M   15G   1% /run
tmpfs            15G     0   15G   0% /sys/fs/cgroup
tmpfs           3.0G     0  3.0G   0% /run/user/1000
tmpfs           3.0G     0  3.0G   0% /run/user/0
```
# yum repolist enabled
```
Loaded plugins: fastestmirror
base                                                                                                                                       | 3.6 kB  00:00:00
extras                                                                                                                                     | 3.4 kB  00:00:00
updates                                                                                                                                    | 3.4 kB  00:00:00
(1/4): base/7/x86_64/group_gz                                                                                                              | 156 kB  00:00:00
(2/4): extras/7/x86_64/primary_db                                                                                                          | 130 kB  00:00:00
(3/4): base/7/x86_64/primary_db                                                                                                            | 5.7 MB  00:00:01
(4/4): updates/7/x86_64/primary_db                                                                                                         | 3.6 MB  00:00:02
Determining fastest mirrors
 * base: mirror.cs.pitt.edu
 * extras: mirror.vtti.vt.edu
 * updates: mirror.es.its.nyu.edu
repo id                                                                      repo name                                                                      status
base/7/x86_64                                                                CentOS-7 - Base                                                                9,591
extras/7/x86_64                                                              CentOS-7 - Extras                                                                283
updates/7/x86_64                                                             CentOS-7 - Updates                                                             1,134
repolist: 11,008
```

# /etc/passwd
```
saturn:x:2800:2800::/home/saturn:/bin/bash
harley:x:2900:2900::/home/harley:/bin/bash
```

# /etc/groups
```
comets:x:2901:harley
planets:x:2902:saturn
```
