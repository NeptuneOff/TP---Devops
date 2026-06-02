cd TP_WIK_DPS_01
node server.js


cd TP_WIK_DPS_02
docker build -t ping-api .
docker run --rm -p 3000:3000 ping-api