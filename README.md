# BackupAce
This bash  script automates various tasks.
The features of the  script:

Creates a backup directory if it doesn't exist.
Creates database backups for multiple databases.
Compresses backups into a single archive.
Copies backups to a remote server using SCP.
Removes old backups that are more than 7 days old.
Restarts the web server.
Sends an email notification upon completion.
Allows the user to specify the backup directory and the remote server.
Allows the user to specify the databases to backup.
Allows the user to specify the email address to send the notification to.
Displays a help message if the user provides the "-h" or "--help" option.
