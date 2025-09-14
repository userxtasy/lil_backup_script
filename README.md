# lil_backup_script
This is a very small project that basically makes à copy/backup of an file each week and send it to a distant server so you have your backup. 

## Requirements

For security reasons you will need a user for backup on your distant server. This user will only have access to the backup file.

  sudo adduser backup_usr     //create the user 

We will need to create a jail with the chroot tool. 
