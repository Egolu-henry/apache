
## Hosting a custom webpage using apache2 

### Tools required include vm, access to internet, booting up the enviroment using vagrant up and vagrant ssh

#### Then install the necessary dependencies using sudo apt upgrade and install

1. `upgrade and installation of apache2 and git `

![mkdir](/apache/update.PNG)

![mkdir](/apache/install%20apache.PNG)

![mkdir](/apache/install%20git.PNG)

2. ` installation is complete, create a new directory and cd into it `

![mkdir](/apache/mkdir%20host.PNG)

3. ` git clone the custom page in this directory `

![mkdir](/apache/git%20init.PNG)

![mkdir](/apache/git%20clone.PNG)

4. ` create the index.html file and other files in the /etc/www directory and copy contents of the page we want to host into it `

![mkdir](/apache/copy-file.PNG)

5. `creating the config file in the /etc/apache2 directory and edit the file to include the root document using nano or vi`

![mkdir](/apache/conf.PNG)

![mkdir](/apache/nano%20conf.PNG)

![mkdir](/apache/nano%20edit.PNG)

6. `disable the default page and enable the new configured page`

![mkdir](/apache/enable-sites.PNG)

7. ` reload the apache page using sudo systemctl reload apache2 and you can verify the status using sudo systemctl status apache2.service `


8. `you can view the hosted page using http://127.0.0.1:8080/ `

![mkdir](/apache/site-hosted.PNG)







