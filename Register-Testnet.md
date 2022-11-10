# Deinfra Registration Testnet

![photo_2022-10-30_11-19-09](https://user-images.githubusercontent.com/94878333/198862408-531040d6-e50e-4419-94f2-bd8bcf026e3e.jpg)

## Install Tools

```
wget -qO deinfra.sh https://raw.githubusercontent.com/sipalingnode/Deinfra/main/deinfra.sh && chmod +x deinfra.sh && ./deinfra.sh
```

## Check Docker
```
docker ps
```

## Check Node
```
apt install jq
```

```
curl http://IPVPS:44000/api/node/status | jq
```
***IPVPS ganti dengan ip vps kalian***

### Get the Tea Ceremony client and token | start tea-client

## Install Screen 

```
sudo apt install screen 
```

```
sudo ufw allow ssh
sudo ufw enable
```

```
ufw status
```

## Get the Tea Ceremony client

```
wget https://tea.thepower.io/teaclient
```

## Give perms

```
chmod +x teaclient
```

## Start client

***Tunggu sampe dapet token di botnya***

***Contoh*** ![Screenshot (269)](https://user-images.githubusercontent.com/94878333/198863606-4f532a1c-699c-43d2-83df-edbac2056827.jpg)

***Kalo dah dapet baru lanjut step dibawah***

```
screen -S deinfra
```

```
./teaclient -n <node name> <token>
```
***Kalo dah jalan langsung CTRL+AD***

***Note : Jika ingin melihat kembali ke screen bisa menggunakan `screen -rd deinfra`***
