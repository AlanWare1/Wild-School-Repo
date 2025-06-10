#### Configuration du fichier etc/asterisk/user.conf

[general]
hasvoicemail = yes  
hassip = yes  
hasiax = yes  
callwaiting = yes  
threewaycalling = yes  
callwaitingcallerid = yes  
transfer = yes  
canpark = yes  
cancallforward = yes  
callreturn = yes  
callgroup = 1  
pickupgroup = 1  
nat = yes  
;  
;    
[88012]  
;  
ullname = Stephane GROOT  
;description = pinpin de la quete         ; Used to provide a description of the  
                                          ; peer in console output  
email = sgroot@osef.com  
secret = 0000  
dahdichan = 1  
hasvoicemail = yes  
vmsecret = 1234  
hasiax = no  
hash323 = no  
hasmanager = no  
callwaiting = no  
context = marketing  
host = dynamic  
disallow = all  
allow = ulaw  
hassip = yes  
username = sgroot  
mailbox = 88012@ff  
