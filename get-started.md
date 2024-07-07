# Get Started

Documentation for the Nero Pterodactyl Client Dashboard

## :zap:  Fast implementation  
  Use pm2:<br/>
  ```JavaScript
//Step 01:
Install pm2. (Guide below.)

//Step 03:
cd
git clone https://github.com/v182/nero nero
cd nero

//Now change settings.yml to your likings (required: panel url & api key)

npm install
pm2 start index.js
```
___
Or, use the Pterodactyl Panel:
```JavaScript
//Step 01:
Install the discord.js generic egg and create a server with that egg

//Step 02:
Drop the Files in ur Server and edit the settings.yml

//Note: If u need Help just feel free to join the Discord or Report the Issue on GitHub.
``` 
  
<br/><br/><br/>
## :tada:  How to install pm2:

**Step 01:**
<BR/>Debian/Ubuntu:
  ```JavaScript
---------- Install Node.js v18.x ---------- 
$ curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
$ sudo apt-get install -y nodejs

---------- Install Node.js v12.x ----------
$ curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
$ sudo apt-get install -y nodejs
  ```
___
CentOS/RHEL and Fedora:
  ```JavaScript
---------- Install Node.js v18.x ---------- 
$ curl -sL https://rpm.nodesource.com/setup_18.x | bash -

---------- Install Node.js v12.x ----------
$ curl -sL https://rpm.nodesource.com/setup_12.x | bash -
  ```

**Step 02**
  ```JavaScript
---------- Install PM2 ---------- 
$ sudo npm i -g pm2
  ```

  
Congratulations! You have now installed Nero. If you installed using the first method we recommend you to now go to the [Webserver](/webserver) part.