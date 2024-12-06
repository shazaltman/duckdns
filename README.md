sudo apt update -y
sudo apt install git -y
git clone https://github.com/shazaltman/duckdns.git
cd duckdns
chmod +x duckdns-docker_compose
sudo ./duckdns-docker_compose
