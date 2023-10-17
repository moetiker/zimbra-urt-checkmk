# zimbra-urt-checkmk
Checkmk local check for Zimbra Reporting Tool

The sctip reads the last file from the Reporting Tool 
under `/opt/zurt/data/mailboxes-*.csv`

add the script to 
```
/usr/lib/check_mk_agent/local/3600/zimbralicreport
```
![image](https://github.com/moetiker/zimbra-urt-checkmk/assets/631883/fa333552-9f63-47a2-a077-915c01dde7e6)
![image](https://github.com/moetiker/zimbra-urt-checkmk/assets/631883/44d92526-c285-467a-b2b0-edf912da0f35)

