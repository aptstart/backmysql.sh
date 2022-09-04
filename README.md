#! /bin/bash
mysqldump -uroot -p'Password' database_name | gzip > /home/backup/database_name_'date +%Y%m%d%H%M'.sql.gz
