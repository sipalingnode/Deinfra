# Update Deinfra (Khusus yang udah dapet token)

## Install Erlang
```
sudo apt update
sudo apt install curl wget gnupg apt-transport-https -y
```
```
curl -fsSL https://packages.erlang-solutions.com/ubuntu/erlang_solutions.asc | sudo gpg --dearmor -o /usr/share/keyrings/erlang.gpg
echo "deb [signed-by=/usr/share/keyrings/erlang.gpg] https://packages.erlang-solutions.com/ubuntu $(lsb_release -cs) contrib" | sudo tee /etc/apt/sources.list.d/erlang.list
sudo apt update
sudo apt install erlang-base erlang-public-key erlang-ssl
```
