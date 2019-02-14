# PostgreSQL Backup-Restore için

For Back-up: 

     $ pg_dump -U <user_name> <database> -Fc  -f {filename.xyz} 

Compress ettik, halilyle oluşan dosya binary. pg_restore ile alalım.

For Restore

    pg_restore -U <user_name> -d <database> {filename.xyz}
