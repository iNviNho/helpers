# Helpers
Different helpers for different languages and situations

# BASH_ALIASES
dps alias will show all docker container with modified information

*bash_aliases*

# SSH TUNNEL
For SSH tunneling make sure to set properly username on the host and server hostname

*create_ssh_tunnel*

# CERBOT
In order to use certbot, don't forget to setup:
- CAA DNS record on host with tag issue for current domain
- certbot command creates 2 certificates (1 for domain, 1 for domain with www prefix)
- I suggest you to spin up temporary webserver for creating certs (maybe nginx|apache should be stopped for a while)

*create_certbox_certs -d*  
*after_certbox_create -d*

Happy using :)
