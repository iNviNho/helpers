# Helpers
Different helpers for different languages and situations

# SSH TUNNEL
For SSH tunneling make sure to set properly username on the host and server hostname

# CERBOT
In order to use certbot, don't forget to setup:
- CAA DNS record on host with tag issue for current domain
- certbot command creates 2 certificates (1 for domain, 1 for domain with www prefix)
- I suggest you to spin up temporary webserver for creating certs (maybe nginx|apache should be stopped for a while)

Happy using :) 
