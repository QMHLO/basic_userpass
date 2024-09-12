# How to create Username and Password for basic url

## Generate Username And Passoword Link
You can generate a username and password hash for Basic Authentication using this online tool:
- https://www.web2generators.com/apache-tools/htpasswd-generator

## Get Server Directory
Use the following PHP code to get your server directory in index.php
```
<?php echo getcwd(); ?>
```

### Example server directory

- /home/qualyxs001/qualy.jp/

## Create .htaccess file

```
AuthUserFile "/home/qualyxs001/qualy.jp/.htpasswd"
AuthName "Member Site"
AuthType BASIC
require valid-user
```

## Create .htpasswd file

```
htet:$apr1$zabrmktn$2JDz1zuMyB.wFDOK95E/R1
```

## Changes Upload files
