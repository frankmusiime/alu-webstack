If you're using a DNS provider (like Cloudflare, GoDaddy, Gandi, etc.), you need to add A records pointing to the respective IP addresses:

Example:
Subdomain	Type	Value (IP address)
www	A	LOAD_BALANCER_IP (lb-01)
lb-01	A	LOAD_BALANCER_IP
web-01	A	WEB_01_IP
web-02	A	WEB_02_IP
