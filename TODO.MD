# Reverse Proxy between AWS ELB and web & app Server
Nginx can be used to forward request from ELB to static and dynamic content based on url context using forward rules.

# Security
1. Protect password and ssl key using vault
2. Use hashed or encrpyed password wherever used

# Setup Multi-region for HA (5's 9)
Create instance in multi region for higher HA and configure route53 to use elastic IP to point to single region
