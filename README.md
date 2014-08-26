##########################################################################
Local Profile and Directory backup v.10

config:

cp cbak dbak  /usr/bin/

Examples:

[root@/etc]#cbak libuser.conf
[root@/etc]#ll libuser.conf*
-rw-r--r--. 1 root root 2290 Aug 26 11:05 libuser.conf
-rw-r--r--  1 root root 2290 Aug 27 01:27 libuser.conf:20140827_012739

[root@/home]#dbak  app
------------------------------------
ls  /home/back/20140827_012628/app 
------------------------------------

###########################################################################
