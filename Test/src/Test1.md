You are a networking and home‑AV design assistant. Design a wired and wireless home network plus basic camera and surround‑sound setup for a newly built 5‑bedroom single‑family home with:

- Prewired ethernet to multiple rooms and some exterior camera locations.
- A central low‑voltage panel where all cables terminate.
- One main TV in the great room, and several laptops and devices that mostly use Wi‑Fi.
- 3–4 outdoor PoE cameras with local recording (no mandatory cloud).
- A 5.1 surround sound prewire in a great room of roughly 15×17 feet.

Requirements:

1. Networking
    - Propose one or more router/firewall options suitable for home use with support for VLANs, DNS control, and simple VPN.
    - Recommend a managed PoE switch with at least 16 ports to support:
        - All prewired room drops
        - 3–4 PoE cameras
        - 2–3 wired access points
        - Some spare capacity for future devices
    - Recommend Wi‑Fi 6 (or better) access points, enough to cover a 5‑bedroom home with a single SSID.
    - Assume the internet connection is up to 1 Gbps today but may increase in the future; suggest how to keep the design “10G‑ready” without unnecessary cost.
2. Cameras and recording
    - Recommend 3–4 outdoor‑rated PoE cameras with good low‑light performance and support for dual streams (main + sub) and open or documented protocols suitable for local NVR or Frigate‑style setups.
    - Recommend an NVR or local server approach with on‑premise storage, including:
        - Type of device (mini PC, NAS, integrated NVR, etc.)
        - Recommended storage capacity and drive type for typical 7–14 day retention at 3–4 cameras.
3. TV and AV
    - There is one main TV in the great room (around 60 inches) mounted on drywall, with the mount already purchased and power tools available.
    - Recommend:
        - A suitable 5.1 AV receiver for a 15×17 ft room (no need for high‑end audiophile gear).
        - A budget‑friendly 5.1 speaker configuration (bookshelf/satellite + sub is fine) that works well in this room size and uses the existing prewire.
    - Do not assume a need for advanced 3D audio (Atmos) unless it can be done with minimal extra cost and complexity.
4. Topology and wiring
    - Provide a clear text description of the physical topology:
        - How the modem connects to the router
        - Router to PoE switch
        - PoE switch to patch panel and from there to room jacks, cameras, and access points
    - Include a suggested port‑mapping scheme for a 16‑port PoE switch (e.g., which ports to use for TV, rooms, cameras, APs), without referring to any specific model names.
5. Cost and complexity
    - For each major component category (router, switch, APs, cameras, NVR/server, AVR, speakers), provide:
        - A typical price range (not brand‑specific)
        - A brief note on DIY difficulty (easy / medium / hard) for a homeowner comfortable with basic tools and simple network configuration.
    - Give at least two full‑system variants:
        - A “value‑optimized” system that is reliable and good for most home users.
        - A “performance‑oriented, 10G‑ready” system that makes sense if the user later adds a fast NAS or heavy local file transfers.
