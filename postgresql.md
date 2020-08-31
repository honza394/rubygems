# Poznámky k Postgresql na WSL

https://github.com/michaeltreat/Windows-Subsystem-For-Linux-Setup-Guide/blob/master/readmes/installs/PostgreSQL.md

**start**
sudo pg_ctlcluster 10 main start
sudo -u postgres psql

**uživatel**
postgres
phoenix

**změna hesla**
sudo -u postgres psql
\password postgres
\q

**ukončení postgres**
\q

## PgAdmin

admin email: postgres@localhost
admin passwd: phoenix