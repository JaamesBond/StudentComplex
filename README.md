# StudentComplex
Welcome to our project that attempts to design a simple and secure internal network for a small student building. It has a web server running on a RaspberryPi 4 that displays some information about the room's tenants and the room's power consumption at any point in time. It also runs a proxy which does some filtering and should improve user experience and a dedicated adblocker, which blocks tracking, malicious sites and some ads. All the filtering and adblocking happens across the network, so every device connected to the network will benefit from it.

Hardware required:
  - QNO Security Router
  - Home Router
  - RaspberryPi 4
  - NETIO Power Cable
  - At least 3 internet cables
  - A laptop with wifi

Software required:
  - RaspbianOS for the RaspberryPi
  - Any OS for the laptop
  - Any SSH client, MobaXterm was used in our case

# Now let's get started
On the RaspberryPi, you should have RaspbianOS installed. If not, there is a very good and clean tutorial [here](https://www.raspberrypi.com/documentation/computers/getting-started.html#installing-the-operating-system).

Now let's proceed to the first step, setting up the backbone of the web server, a LAMP(Linux, Apache, MySQL, PHP) server. That is very straightforward to do and I found [this](https://randomnerdtutorials.com/raspberry-pi-apache-mysql-php-lamp-server/) amazing tutorial which helped us a lot.

Now that the server is up and running, the next step is to set up Joomla!, which is a lighter variant of WordPress. It will allow us to easily deploy a good-looking interface while organising all the files nicely. For this part, 
