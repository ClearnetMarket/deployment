
# Freeport Setup for local development

This project has been made as simple as possible to get up and running.
Databases will populate automatically.  You just need latest docker or docker-compose.



## Run Locally

Clone the project

```bash
git clone https://github.com/ClearnetMarket/deployment.git
git clone https://github.com/ClearnetMarket/dbdata.git
git clone https://github.com/ClearnetMarket/frontend.git
git clone https://github.com/ClearnetMarket/backend.git
git clone https://github.com/ClearnetMarket/wallet_btc.git
git clone https://github.com/ClearnetMarket/wallet_xmr.git
git clone https://github.com/ClearnetMarket/wallet_bch.git
git clone https://github.com/ClearnetMarket/coinprices.git
```
Make sure Docker is installed (newest version)
```bash
  cd deployment
  sudo docker network create freeport
  sudo docker-compose -f docker-compose-dev.yml up
```

This will dockerize the entire application.  It might take 10-30 mins
for the database depending on your pc speed.

Login
Username: User
Password: Password

