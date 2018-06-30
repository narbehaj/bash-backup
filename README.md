# Simple backup script for GNU/Linux servers
#### Simple bash backup script V1.0

You need megatools in order to upload your backup file to MEGA. Download megatools from http://megatools.megous.com/

### Main features

- Backup custom files and directories
- Backup MySQL/PostgreSQL/MongoDB databases
- Copy/SCP/FTP to another server or mounted media
- Upload to MEGA.nz cloud
- Send a notification to your email
- Logging all the activities
- Encrypts backup file using GPG
- Backup multiple Mariadb/mysql docker containers

### Edit the configuration and run
```
sudo bash backup.sh
```

### syntax for Backup Docker Mariadb/Mysql
```
containerID:::user:::password:::database
```

### Changelog

**V1.0**

- Added MongoDB backup support

### Main Requirement

- tar
- gzip 
- bzip2

### TODO 

- [ ] Docker volume backup support 
- [ ] rsync directory files ( backup public or huge files) 
