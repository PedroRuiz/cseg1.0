# cseg1.0
cseg1.0 creates easily full and incremental backups from linux terminal

# help
type cseg to get help about it.

# Adapt your variables
Once you get the script edit and change the BASE variable at line 18 to express your own directory to dump. Then edit at line 24 the TARGET variable to fix the device to dump and restore from backups.

# Keep only a full backup in cseg1.0 folder
To restore data, just type 'cseg restore', it firstly will ask you about the date of the full backup, and then it will restore over all incremental in order of creataion. For this reason is very important to keep only a full backup with several incrementals.
