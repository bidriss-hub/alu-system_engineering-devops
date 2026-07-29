# Load balancer

This project configures two web servers behind an HAProxy load balancer.

## Files

- 0-custom_http_response_header: Adds X-Served-By header to nginx responses.
- 1-install_load_balancer: Installs and configures HAProxy with round-robin balancing.
