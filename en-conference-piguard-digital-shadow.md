<section data-background-image="https://nothing2hide.org/fr/wp-content/uploads/sites/2/2026/07/Fichier-4@33.33x.png">
<aside class="notes">
Note: Opening slide. Digital Shadows was organized by Streaming Asylum, in partnership with Media Challenge Initiative and Nothing2Hide, as part of Cybersecurity/Digital Safety Month. This talk is part of the PiGuard demo track ("Hacker Escape Tent").
</aside>
</section>



## Who we are

- **Nothing2Hide** - NGO fighting for digital rights, press freedom & digital security
- We run a 24/7 helpline for journalists, activists & civil society
- Today's focus: **PiGuard**, our censorship circumvention hardware



![Digital Shadows: Take Back Control!](https://nothing2hide.org/fr/wp-content/uploads/sites/2/2026/07/Digital-Shaddows-Poster-600.jpg)



## Why are we here?

- Surveillance, disinformation and digital threats increasingly target **marginalized communities**
- Journalists, refugees, young activists - often working in **hostile digital environments**
- Circumventing censorship isn't a luxury, it's a **survival tool** for information access
- PiGuard was built to make circumvention **simple, cheap and hard to block**



# 1. What is PiGuard?



## Elevator pitch

> A **plug-and-play** censorship circumvention box.


- Turn PiGuard on, connect it to the Internet
- PiGuard creates a **WiFi network**
- Anyone connected gets an **encrypted, uncensored connection**
- No technical skill required to *use* it - only to *set it up*



## Under the hood


![Raspberry Pi](https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2016/01/raspberry-pi-cases.jpg) <!-- .element: style="height:420px; float:right; margin-left:30px; border-radius:8px;" -->


- A **Raspberry Pi** (cheap, easy to find, easy to replace)
- Running **WireGuard VPN** technology
- In highly repressive contexts, it can fall back to **Tor + obfs4 (obsproxy)** when VPN protocols themselves are blocked



## What PiGuard is


- **Easy to use**: it just needs power + Ethernet, then it's a WiFi hotspot
- **Cheap**: indicative full kit price ≈ **85 €**
- **Resilient**: automatic server-hopping makes it hard to block
- **Adaptable**: VPN or Tor, chosen from a simple admin interface



## What PiGuard does *not*


- A VPN (PiGuard included) **does not secure your network**
- It's a **"dumb pipe"**: it encrypts and carries traffic - legitimate document or malware, it doesn't care
- If a connected device is already compromised, **data still leaks** through the VPN
- That's why every PiGuard deployment comes with a **training component**



## When should you use it?


- **Simple network**: protect a handful of devices directly
- **Complex network**: protect an entire newsroom / office network
- Best suited for **fixed locations**: newsrooms, community centers, safe houses



## Who is it for?


Anyone who needs *group-level*, low-maintenance circumvention - not just a personal app


- **Journalists & newsrooms** operating under censorship or surveillance
- **Activists and civil society organizations**
- **Refugees and displaced communities** needing safe access to information
- **Young activists / community hubs** in contexts of restricted connectivity




## The rules of the road


- PiGuard runs on Nothing2Hide's **WireGuard infrastructure**
- Users must **respect fair use** of the network
- No illegal content that could jeopardize the whole project (copyright infringement, etc.)
- We **do not monitor content** - but we **do measure bandwidth usage**



# 2. Using PiGuard



- Connect your devices to the **piguard** WiFi network
- Default WiFi network name (SSID): `piguard`
- In a web browser Open up http://<PIGUARD_IP_ADDRESS>:8000/
- Default login is provided by Nothing2Hide (**change it on first login**)


![first connection](https://repo.nothing2hide.org/PiguardV2/Documentations/Wifi-Portal/images/piguard_login_page.png)


- Home page shows a **green "Connected"** status if all is well


![Connection](https://repo.nothing2hide.org/PiguardV2/Documentations/Wifi-Portal/images/piguard_network.png)



| Mode | When to use it |
|---|---|
| **VPN (WireGuard)** | Standard censorship - auto-switches server if blocked |
| **Tor + obfs4 (obsproxy)** | Highly authoritarian contexts where the VPN *protocol itself* is blocked |


Switching is done directly from the admin interface - no reflashing needed.



# Recap


- PiGuard = plug-and-play box combining **Raspberry Pi + WireGuard (+ Tor fallback)**
- Built for **groups**, not just individuals: newsrooms, communities, safe houses
- A VPN secures the *pipe*, not your *devices* - training matters
- Fair use of shared infrastructure keeps the project alive for everyone
