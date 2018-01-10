
This is a very simple One file/One Page PHP frontend for Vnstat
I did not meant to over complicate the code for easy modification, it is simple and dirty as i like it. 


##  **The license notices**

	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

	You should have received a copy of the GNU General Public License
	along with this program.  If not, see <http://www.gnu.org/licenses/>.

## **Debian Installation**
**1- Install vnstat and vnstati and run their Deamons :**    
	sudo apt-get install vnstat vnstati
    sudo vnstat -u -i eth0
    sudo /etc/init.d/vnstat start
    (make sure they are work perfectly)
    sudo ps -f | grep vnst
    
**2- Copy or Git the project to your webserver directory**    
    cd /to/you/web/server/
    git clone https://github.com/iranianpatriot/vnstat-very-simple-php-frontend.git
    
    
**3- Don't forget to set permissions :**	
	sudo chown www-data:www-data vnstat-very-simple-php-frontend -R
    
## **ScreenShot**    

![](https://raw.githubusercontent.com/iranianpatriot/vnstat-very-simple-php-frontend/master/Screenshot.jpg)
