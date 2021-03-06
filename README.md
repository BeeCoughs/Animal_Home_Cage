# Animal Home Cage Monitoring System with GPIO Controls #

The animal home-cage monitoring system is a raspberryPi based solution for automated behavior
monitoring of rodents. This system uses a picam (prefereably IR) to record video in the home-cage.

In this implementation, the RPi runs an apache webserver that streams video allowing the user to remotely monitor animal behavior. In addition, the system allows the user to change the camera settings and the interaction between the RPi and the peripherials (LEDs, speakers, etc) in the cage via the GPIO pins.


## Installation ##

- Step 1: Install Raspbian on your RPi

- Step 2: Attach camera to RPi and enable camera support (http://www.raspberrypi.org/camera)

- Step 3: Update your RPi with the following commands:

```
sudo apt-get update

sudo apt-get dist-upgrade

```

- Step 4: Clone the code from github and run the install script with the following commands:

``` 
git clone https://github.com/surjeets/Animal_Home_Cage.git

cd Animal_Home_Cage

./install.sh

```
## Commands ##
To start the interface run:

```
cd Animal_Home_Cage

./start.sh

```

To stop the interface run:

```
cd Animal_Home_Cage

./stop.sh

```
To remove the interface run:

```
cd Animal_Home_Cage

./remove.sh
```
