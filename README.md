## I prompted AI to help create a custom rules template to generate the alerts
You can find [the custom rule file](./snort_rules/my.rules) in the link.

**Sample prompt:** \
Create a custom rules template\
Also include cerber, evil redirector and RIG

## I ran snort 3 on PCAP file using my custom rules
You can find [the alert file](./logs/alerts.txt) in the link.

**Sample prompt:** How to generate the alert file in snort 3 using my custom rules, also save the alert to a txt file

**Command:**\
cd ~/CW1 \
sudo snort -c /usr/local/etc/snort/snort.lua -R /usr/local/etc/snort/rules/my.rules -r COMP3010HK_CW1.pcap -A alert_fast -q > ./logs/alerts.txt

## I use AI to analyse and generate a draft on the PCAP and alerts file, then I audited the draft against the raw evidence.

**Sample prompt:**\
Analyse the PCAP file provided\
Analyse the alert file provided