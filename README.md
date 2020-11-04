# Network_week6

6th Week Homework : netfilter-test

sudo iptables -A OUTPUT -j NFQUEUE --queue-num 0
sudo iptables -A INPUT -j NFQUEUE --queue-num 0

터미널 창에 입력 후, 본 프로그램 실행
