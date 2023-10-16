# zimbra-urt-checkmk
Checkmk local check for Zimbra Reporting Tool

The sctip reads the last file from the Reporting Tool 
under `/opt/zurt/data/mailboxes-*.csv`

add the script to 
```
/usr/lib/check_mk_agent/local/3600/zimbralicreport
```
