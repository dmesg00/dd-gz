`dd-gz` - dd compressing on the fly 

## Create backup:

```
dd-gz backup /dev/<device> /path/<output>.gz
```

Example:

```
dd-gz backup /dev/sdc /home/backup/sdc-backup.gz
```

## Restore backup:

```                                                                                                                                                                                                                  
dd-gz restore /path/<input>.gz /dev/<device>                                                                                                                                                                       
```  

Example:

```
dd-gz restore /home/backup/sdc-backup.gz /dev/sdc
```

## How to install:

```
git clone https://github.com/dmesg00/dd-gz
cd dd-gz
sudo make install 
```

## How to uninstall:

```
git clone https://github.com/dmesg00/dd-gz
cd dd-gz
sudo make uninstall 
```

## Dependencies
* sh
* dd
* gzip

