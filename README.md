# Azure VM Nginx Deployment

A static HTML page hosted on an Ubuntu virtual machine in Azure using Nginx.

## What I did

1. Created an Ubuntu VM in the Azure Portal.
2. Configured inbound access for SSH (TCP 22) and HTTP (TCP 80).
3. Connected to the VM over SSH and installed Nginx.
4. Created a custom page directly on the VM at `/var/www/html/index.html`.
5. Tested the page with `curl` and opened it in a browser using the VM's public IP.
6. Copied the deployed HTML file to my Mac using `scp` and tracked it with Git.

## Deployment screenshot

![Custom Nginx page running on my Azure VM](screenshot.png)
