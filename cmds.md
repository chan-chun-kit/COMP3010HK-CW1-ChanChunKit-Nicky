cd ~/CW1
sudo snort -c /usr/local/etc/snort/snort.lua -R /usr/local/etc/snort/rules/my.rules -r COMP3010HK_CW1.pcap -A alert_fast -q > ./logs/alerts.txt