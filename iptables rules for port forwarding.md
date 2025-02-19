# Redirect the 80 traffic to port 8080
iptables -A PREROUTING -t nat -p tcp --dport 80 -j REDIRECT --to-ports 8080 

# Save The rule
iptables-save
