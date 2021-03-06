

System

```
uname -a        # View kernel/operating system /CPU information  
head -n 1 /etc/issue   # View the operating system version  
cat /proc/cpuinfo      # View CPU information  
cat /proc/meminfo       #View memory information
hostname               # View computer name  
lspci -tv              # List all PCI devices  
lsusb -tv              # List all USB devices  
lsmod                  # Lists kernel modules loaded  
env                    # View environment variables  
```   

Resources

```
free -m                # View memory usage and swap usage  
df -h                  # View partition usage  
du -sh <目录名>        # View the size of the specified directory  
grep MemTotal /proc/meminfo   # View total memory  
grep MemFree /proc/meminfo    # View the amount of free memory  
uptime                 # View system running time, number of users, load  
cat /proc/loadavg      # View system load  
```   

Disk and partition

```
mount | column -t      # View the status of a pending partition  
fdisk -l               # View all partitions  
swapon -s              # View all swap partitions  
hdparm -i /dev/hda    # View disk parameters (only for IDE devices)  
dmesg | grep IDE       # View IDE device detection status at startup  
```

Net

```
ifconfig               # View the properties of all network interfaces  
iptables -L            # View firewall Settings  
route -n               # View routing table  
netstat -lntp          # View all listening ports  
netstat -antp          # View all established connections  
netstat -s             # View network statistics  
```  

Process

```
ps -ef`                 # View all processes  
top                   # Real-time display of process status  
```  

User

```
w                      # View active users
id <username>            # View the specified user information
last                   # View the user login log
cut -d: -f1 /etc/passwd   # View all users of the system
cut -d: -f1 /etc/group    # View all groups of the system
crontab -l             # View the scheduled tasks for the current user
```    

Service

```
chkconfig --list       # List all system services
chkconfig --list | grep on    # Lists all system services started
```  

Program

```
rpm -qa                # View all installed packages
```
