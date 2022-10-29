# Deinfra Registration Testnet

```
sudo apt update -y && sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin && sudo apt install docker-compose
```

```
docker run -d -p 44000:44000 --name tpnode thepowerio/tpnode
```

```
apt install jq
```

```
curl http://IPVPS:44000/api/node/status | jq
```
***IPVPS ganti dengan ip vps kalian***
