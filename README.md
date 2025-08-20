# CCNA Labs

## Documentation and practice labs for CCNA certification using Jeremy’s IT Lab course and Neil Anderson’s Gold Standard Bootcamp. Includes Packet Tracer configurations, notes, and step-by-step guides.

# Jeremy's IT CCNA Network Topology Lab 01

![Jeremy's IT CCNA Network Topology Lab 01 image](https://i.imgur.com/wLeRynY.png)


**Goal:** Connect the New York Branch to the Tokyo Branch.

---

In this lab the New York Branch has `PC1` and `PC2` connected to `SWITCH1`.

`SWITCH1` connects to `ROUTER1`, which then connects to `FIREWALL1`.

From there, packets move across the network to `ROUTER2` at the Tokyo Branch.

`ROUTER2` connects to `FIREWALL2`, which then connects to `SWITCH2`.

`SWITCH2` connects to `SERVER1` and `SERVER2`.

We also have an `ATTACKER` laptop connected to the **INTERNET** between the network backbone and `FIREWALL2`. This represents outside threats trying to access the network.

---
# Jeremy's IT CCNA Connecting Devices Lab 02
**Goal:** Select the appropriate cable for each Cisco networking device.

![Jeremy's IT CCNA Connecting Devices Lab 02 image](https://i.imgur.com/RCr9Yjh.png)

1. End Points to Switches

Connect ``PC1`` ⏩ ``SW3`` using a straight-through cable.

Connect ``PC2`` ⏩ ``SW4`` using a straight-through cable.

Connect ``PC3`` ⏩ ``SW7`` using a straight-through cable.

Connect ``SRV1`` ⏩ ``SW8`` using a straight-through cable.

2. Switch to Switch Connections

Connect ``SW3`` ⏩ ``SW1`` using a crossover cable.

Connect ``SW4`` ⏩ ``SW2`` using a crossover cable.

Connect ``SW1`` ⏩ ``SW2`` using a crossover cable.

Connect ``SW5`` ⏩ ``SW6`` using a crossover cable.

3. Routers to Switches

Connect ``R2`` ⏩ ``SW1`` using a straight-through cable.

Connect ``R2`` ⏩ ``SW2`` using a straight-through cable.

Connect ``R4`` ⏩ ``SW5`` using a straight-through cable.

Connect ``R4`` ⏩ ``SW6`` using a straight-through cable.

4. Router to Router Links

Connect ``R1`` ⏩ ``R2`` since the distance is 50 meters, a fiber optic cable multimode is needed.

Connect ``R4`` ⏩ ``R3`` since the distance is 250 meters, i will use a multimode fiber.

Connect ``R1`` ⏩ ``R3`` since the distance is 3 kilometers, i will use a single-mode fiber cable.

---
# Cisco CCNA 200-301 Gold Bootcamp Lab 04
---