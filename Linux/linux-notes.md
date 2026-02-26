# Linux Notes with Usage Examples

## ls
List directory contents.

Example:
ls -la

## cd
Change directory.

Example:
cd /var/log

## chmod
Change file permissions.

Example:
chmod +x script.sh   # Make script executable

## df -h
Check disk usage in human-readable format.

Example:
df -h

## free -h
Check memory usage.

Example:
free -h

## ps aux
View running processes.

Example:
ps aux | grep nginx

## kill
Terminate a process.

Example:
kill 1234   # Replace 1234 with PID

## top
Display real-time system information.
Example:
```
top
```
## grep
Search for a pattern in files.
Example:
```
grep "error" /var/log/syslog
```
## find
Search for files in a directory hierarchy.
Example:
```
find /home/user -name "*.txt"
```
## tar
Archive files.
Example:
```
tar -czvf archive.tar.gz /path/to/directory
```
## ssh
Connect to a remote server.
Example:
```
ssh user@remote-server
```
## scp
Copy files between hosts.
Example:
```
scp file.txt user@remote-server:/path/to/destination
```

