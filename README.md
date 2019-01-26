# LinuxServer
Item-catalog project hosted on a aws lightsail server

# Access Details
IP address: 13.243.17.149.

Accessible SSH port: 2200.

Application URL : 13.243.17.149/candymanufacturers

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
