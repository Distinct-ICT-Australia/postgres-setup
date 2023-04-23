
# Intro

We are constantly setting up new databases, but not enough for it to stay at top of mind :( . There is a ripper article on medium we always go back to that has a quick TLDR on the commands we need to run... Always so hard to find though.
Have credited it below.

# Script

```
sudo -u postgres sql
create database mydb;
create user myuser with encrypted password 'mypass';
grant all privileges on database mydb to myuser;
```

# More details

Credit: https://medium.com/coding-blocks/creating-user-database-and-adding-access-on-postgresql-8bfcd2f4a91e
