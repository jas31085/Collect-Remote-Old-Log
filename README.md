
Log Collector
----------------
 
Collect Log File from Archive to local,
I use it to clean server log folder from 7 days older logs

Usage: Archive_Log -f List_Host [-l Log_File]<br>
    -f, --file 				File With hosts and Logs to collect<br>
	   -d, --dir					Local Folder To Collect Logs [default=/var/log/Archive_log/]<br>
    -l, --log 				Log file for script [default=/var/log/Archive_log.log]<br>
    -h, --help 				Display this screen<br>
<br>
Example File: --- NO EMPTY LINE --- <br>
IP - path - hostname<br>
10.10.1.8 - /var/log/httpd - vbe-backup-prod01 - httpd<br>
10.10.2.5 - /var/log/ - vlb-app-prod01.csm.it - log<br>

<br>
<br>
Archive_log-NFS-First - Untested NFS

<br>
fell free to use and correct them,
<br>
Thanks.
