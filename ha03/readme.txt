GROUP DETAILS:
Anushree.J   1KS17CS011
Deekshitha.R  1KS17CS021
Lavanya.V     1KS17CS037

DESCRIPTION:
According to our question A04, USN: 1KS17CS011 where value is X=21 and Y=11
Rule 1: sudo iptables -I OUTPUT -d 192.168.56.1 -p icmp --icmp-type 8 -m limit --limit 21/minute --limit-burst 11 -j ACCEPT

RULE 2: sudo iptables -A OUTPUT -d 192.168.56.1 -p icmp --icmp-type 8 -j DROP

ping -c 60 192.168.56.1


CHALLENGES FACED:
While typing commands went wrong with few syntax and then corrected it. 


