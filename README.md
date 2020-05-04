# home-automation
raspberry pi based home automation project heavily dependent on docker

1st most important command is to update and upgrade your Raspbian system

```
sudo apt-get update && sudo apt-get upgrade -y
```
## Docker Installation
here is the code for installing docker on raspberry pi - [Referance](https://phoenixnap.com/kb/docker-on-raspberry-pi)

1st run the following script
```
curl -fsSL https://get.docker.com -o get-docker.sh
```

2nd run the following command
```
sudo sh get-docker.sh
```

3rd adding pi user to docker group
```
sudo usermod -aG docker Pi
```

4th checking docker version
```
docker version
```

## MQTT Mosquitto
this is the communication protocol used for machine to machine light weight - [Referance](https://tewarid.github.io/2019/04/03/installing-and-configuring-the-mosquitto-mqtt-broker.html)
