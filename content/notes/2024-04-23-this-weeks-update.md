+++
title = "This Week's Update"
+++


Things I have been up to while off LinkedIn:

- Working on my home lab by setting up k3s for High Availabilty servers for critical services in the lab
- Learning more about VMs, Nginx, and Reverse Proxies
- Learning about Certbot
- Failing to set up TWO "beginner-friendly" reverse proxy managers
- Learning how to reconfigure Proxmox IP addresses, failing to keep the cluster, and wiping three nodes clean
- Deciding that I'd keep one node out of the cluster for having one less entrypoint to my network[^1]
- Setting up InfluxDB for use of monitoring my Proxmox cluster and separate node in Grafana
- Learning Linux commands such as `fstab`, `lsblk`, and that you can pretty much do everything you need system wide (rebooting, etc), by prefixing `systemctl` to those commands
- Creating my own Docker image and container to fix a bug in a repo I want to use but want it to install dependencies and "just work", as they say
- Installing a self-hosted Git client/website
- Learning that `ini` files are basically the same as `toml` files
- Researching how to use WebSockets in Python or Go to understand how someone could use that to exploit a website/machine by keeping the socket alive and using the website/machine as a C2 server
- Working on creating my own C2 server

I've been at it nonstop these past two weeks, but I am having serious fun.






[^1] I have too many VMs and LXCs now or I'd change the IP to help with this as well.