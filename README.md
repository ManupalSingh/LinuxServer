# LinuxServer
Item-catalog project hosted on a aws lightsail server

# Access Details
IP address: 13.234.17.149.

Accessible SSH port: 2200.

Application URL : 13.234.17.149/candymanufacturers

# Configuration Summary

1. Updated exisitng packages

2. Configured the UFW (SSH access from lightsail console disabled(port 22), enabled access from port 2200)
  allowed basic http server

3. Created user named grader provided it sudo permissions

4. setup secure key exchange mechnism using rsa keys for grader user to log into server

5. Installed Apche2, mod_wsgi, PostgreSql, Python

6. created a linux user named catalog for databse manipulation.

7. Cloned the project from github

8. Setup final application and environment by creating catalog.wsgi file and catalog-app.conf file 

# Essential system packages

1. Apache2
2. mod_wsgi
3. PostgreSQL
4. Python
5. touch (for file creation)
6. nano text editor
7. Git (for cloning directory from github)
8. SQLAlchemy
9. Flask

# Resources utilised

1.  For successfully accessign server through 2200 port SSH
    https://stackoverflow.com/questions/47342988/aws-ssh-port-timeout-after-changing-port-number
2.  Countering package import errors
    https://stackoverflow.com/questions/34461987/python3-importerror-no-module-named-xxxx
    https://stackoverflow.com/questions/48780634/modulenotfounderror-no-module-named-oauth2client-client?rq=1   
3.  No such file or directory error fix
    https://www.pythonanywhere.com/forums/topic/4200/
