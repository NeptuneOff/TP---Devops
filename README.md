cd WIK_DPS_TP01

node server.js


cd WIK_DPS_TP02

docker build -t ping-api .

docker run --rm -p 3000:3000 ping-api


cd WIK_DPS_TP03

docker compose up --build
