cd TP_WIK_DPS_01

docker build -t ping-api .

docker run --rm -p 3000:3000 ping-api