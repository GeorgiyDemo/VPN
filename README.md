### CentOS Server:
>yum install git -y && git clone https://github.com/georgiydemo/VPN && cd VPN && chmod +x docker.sh && ./docker.sh

### Client:
>wget -O "VPN.ovpn" --no-check-certificate <YOUR_SERVER_IP:PORT>