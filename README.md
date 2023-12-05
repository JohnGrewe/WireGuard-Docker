
```
sudo apt install docker.io
```
```
sudo apt install pip
```
```
sudo apt update
```
```
```
```
sudo pip3 install docker-compose
```

```
mkdir -p ~/wireguard/
mkdir -p ~/wireguard/config/
nano ~/wireguard/docker-compose.yml

```

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y

```

```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

```


```
sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
```

```
apt-cache policy docker-ce
```
```
sudo apt install docker-ce -y
```

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```

```
cd ~/wireguard/
docker-compose up -d
```

```
docker-compose logs -f wireguard
```
![0](https://github.com/JohnGrewe/WireGuard-Docker/assets/112670893/6a1a398a-157c-4272-93ac-89812ee138bf)

![0](https://github.com/JohnGrewe/WireGuard-Docker/assets/112670893/fb19d4f6-a0e0-4d21-bf7b-1579e1d638c5)

![0](https://github.com/JohnGrewe/WireGuard-Docker/assets/112670893/ebe92e06-5797-400d-854d-e6d150915d7e)

![0](https://github.com/JohnGrewe/WireGuard-Docker/assets/112670893/942e301c-aae6-4909-9076-95da4668411e)

