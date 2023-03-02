

# Start up the mysql database
mysql -u root -p

# DONT KNOW
source db/schema.sql

# Database configuration
mysql -u root -p -e "CREATE DATABASE IF NOT EXISTS $DB_NAME;"