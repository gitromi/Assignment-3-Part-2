# Assignment-3-Part-2

---

## Create Two Droplets

1. Log into your [DigitalOcean Account](https://www.digitalocean.com/).

2. Click on **Create > Droplets**.

3. Set up the droplets as follows:
   - **Image**: Arch Linux
   - **Plan**: Choose your desired CPU and Memory plan.
   - **Region**: SFO3
   - **SSH Keys**: Add your SSH key.
   - **Tag**: Add the tag "web" to both droplets.

4. Set the **quantity** to 2 and assign unique names (e.g., `web01` and `web02`).

5. Click **Create Droplet** and make note of the **Public IPs** for both droplets.

---

## What is a Load Balancer?

A load balancer is a system that distributes traffic to two or more servers to improve availability and reliability.

---

## Create a Load Balancer

1. Navigate to the **Load Balancer Creation Page** on DigitalOcean.

2. Configure the load balancer:
   - **Choose a Balancer Type**: Regional.
   - **Choose a datacenter region**: San Francisco 3:
   - **Network Visibility**: External (Public)
   - **Connect Droplets**: web

3. Click **Create Load Balancer** and note the **Public IP Address** of the load balancer.

---


