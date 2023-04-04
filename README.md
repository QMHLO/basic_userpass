# How to create Username and Password for basic url

## Generate Username And Passoword Link 
- https://www.web2generators.com/apache-tools/htpasswd-generator

### Example
## Create .htaccess file
```
AuthUserFile "/home/qualyxs001/qualy.jp/htpasswd/.htpasswd"
AuthName "Member Site"
AuthType BASIC
require valid-user 
```
## Create .htpasswd file
```
htet:$apr1$zabrmktn$2JDz1zuMyB.wFDOK95E/R1
```
