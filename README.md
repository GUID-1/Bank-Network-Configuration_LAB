# Bank-Network-Configuration_LAB
Configuring end-to-end communication in a Bank Network topology utilizing switchports, DHCP, trunking, routing protocols, HTTP, DNS, &amp; SVI's

<h1>Bank Network Packet Tracer Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/6SdBQwv79c4)

<h2>Description</h2>
Project consists of a configuring a bank network topology that incorporates the configuration of DHCP, Routing protocols, VLANS, interface vlans, trunk ports, static IP addressing & switchport access mode
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco CLI</b>

<h2>Cisco CLI Commands Used</h2>

- <b>Enable (en)</b>
- <b>Configure Terminal (conf t)</b>
- <b>Do Show Vlan (do sh vlan)</b>
- <b>Do Show Interfaces Status (do sh interfaces status)</b>
- <b>Interface Range (int range)</b>
- <b>Switchport Mode Access (sw mod acc)</b>
- <b>Switchport Access vlan (sw acc vlan)b>
- <b>Do Write (do wr)</b>
- <b>Do Show Run (do sh run)</b>
- <b>Switchport Mode Trunk (sw mod trunk)</b>
- <b>Do Show Controllers Serial (do sh controll se)</b>
- <b>Clock Rate(clock ra)</b>
- <b>Service DHCP (service dhc)</b>
- <b>IP DHCP Pool (ip dhcp pool)</b>
- <b>Network (netwo)</b>
- <b>Default-Router (defaul)</b>
- <b>DNS-Server (dns)</b>
- <b>Domain-Name (domai)</b>
- <b>Encapsulation Dot1q (encap dot)</b>
- <b>CDP Run (cdp run)</b>
- <b>Do Show CDP Neighbor (do sh cdp neighb)</b>
- <b>Do Show CDP Neighbor Detail (do sh cdp neighbor det)</b>
- <b>Do Show IP Interface Brief (do sh ip int bri)</b>
- <b>Router EIGRP (router ri)</b>
- <b>Do Show IP Route (do sh ip rout)</b>
- <b>Do Show IP Route EIGRP (do sh ip rout ri)</b>

<h2>Environments Used </h2>

- <b>Packet Tracer 9.0</b> 

<h2>Configuration walk-through:</h2>

<p align="center">
VLAN & Switchport configuration F1-SW (MGNT): <br/>
<br />
<img src="https://www.image2url.com/r2/default/images/1790657560632-e8177242-b65f-45e5-a76a-19d97fcc35ec.png" alt="Switchport  Configuration" />
<br />
<br />
VLAN & Switchport configuration F1-SW (R&D): <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790657848990-5fcaf9d8-3e54-4bef-9b5f-54567c679aca.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790658767294-524e5594-aead-456c-b5f2-dd13d441955e.png" alt="Switchport Configuration" />
<br />
<br />
VLAN & Switchport configuration F1-SW (HR): <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790658926070-2cce2845-f5b0-434c-87a9-0ebeeabaf86a.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790659759836-39f0c9f9-c90c-4c72-9bd7-216232d6a663.png" alt="Switchport Configuration" />
VLAN & Switchport configuration F2-SW (MRKT): <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790659946383-a1ad61af-5899-4855-affd-73980ff1c82c.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790660336601-49c826ac-e997-4818-887c-6f6a3536f35c.png" alt="Switchport Configuration" />
VLAN & Switchport Configuration F2-SW (FIN):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790660612984-f7aa208a-ae2d-44e4-8e9d-1f0b5ec604d6.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790661069483-c7325b2b-5082-4824-9262-3e64c5cee2f4.png" alt="Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration F2-SW (ACC):   <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790661232166-5853eb5f-d775-49d9-8184-b493f6724859.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790661636215-32c22e9e-b577-405c-9376-6aaf3d5a560f.png" alt="Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration F3-SW (LOG):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790661928099-316a1893-bf2a-4c46-b0bd-336101a932cc.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790662130085-4356904c-00f7-46c6-84a5-3e6c489f7f3c.png" alt="Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration F3-SW (CUST):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790662269509-ab23feba-0a0b-4ae9-a3e7-5998c0bdd9ef.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790663058646-42d69376-156e-41e7-a486-38bb9ceee341.png" alt="Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration F3-SW (GUEST):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790663218475-ead98bbd-dc60-4875-8838-e8b3cb0484e1.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790663332207-91ee4f01-fe95-4f2e-9fb1-c9e904185d02.png" alt="Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration F4-SW (ADMIN):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790663480741-faee557b-4b06-4a09-8ff9-0cb8759afd4a.png" alt="Switchport Configuration" /> 
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790663592322-111a5a81-a33f-47ef-a66a-57cfdd3eddf4.png" alt="Switchport Configuration" />
<br />
<br />
Router Interface Configuration (F3-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788509232524-a345dac9-2453-4443-ba22-4c538fcb89eb.png" alt="Router Config" />
<br />
<br />
Router Clock Rate Configuration (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788509938431-226ba843-6248-49ae-9e05-f62244900e2e.png" alt="Clock Rate Config" />
- Set the clock rate to 64000 for each DCE interface  
<br />
<br />
Router Clock Rate Configuration (F2-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788510169621-f8dacb1a-d7b9-4ec7-926a-af3b0b15d688.png" alt="Clock Rate Config" />
<br />
<br />
Router DHCP Configuration (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788510448507-9315a0ed-e977-4549-8f15-327e9a816977.png" alt="DHCP Config" />
<img src="https://www.image2url.com/r2/default/images/1788510638622-341b58a7-b259-4203-b095-e224c25f6c3a.png" alt="DHCP Config" />
<img src="https://www.image2url.com/r2/default/images/1788510781563-34f082b1-452b-4dbf-8428-931d0e020c1b.png" alt="DHCP Config" />
<br />
<br />
Router Subinterface Configuration (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788522797598-e20a9c94-0508-4b2a-91c9-c9a7b4dc62f4.png" alt="Router Subinterface Config" />
<img src="https://www.image2url.com/r2/default/images/1788523016959-472e6307-fcda-473f-b3c7-08bd3f4e82d4.png" alt="Router Subinterface Config" />
<img src="https://www.image2url.com/r2/default/images/1788523467528-9c28b4a8-0fae-4a1c-8cb0-eebfb7ba1a23.png" alt="Router Subinterface Config" />
<img src="https://www.image2url.com/r2/default/images/1788523596875-0bafd94a-3013-4b9f-9b64-eea522fd0dd6.png" alt="Router Subinterface Config" />
<img src="https://www.image2url.com/r2/default/images/1788523754262-718ce0f2-efe0-4841-91ee-4562291f4fb4.png" alt="Router Subinterface Config" />
<br />
<br />
Router DHCP Configuration (F2-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788524144294-73aac06c-0b05-4b2d-95d8-328e188f1028.png" alt="Router DHCP Config" />
<img src="https://www.image2url.com/r2/default/images/1788524337765-38c7d819-8d16-4f0a-b03c-38da20dfadcd.png" alt="Router DHCP Config" />
<br />
<br />
Router Subinterface Configuration (F2-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788524546175-9586d171-01a0-4d38-88e7-7159369a8a41.png" alt="Router Subinterface Config" />
<br />
<br />
Router DHCP Configuration (F3-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788525025166-1ffc48f1-2841-420a-b31a-178da640674d.png" alt="Router DHCP Config" />
<img src="https://www.image2url.com/r2/default/images/1788525111618-195fb975-0f50-4feb-b0d0-a0463438b9f4.png" alt="Router DHCP Config" />
<br />
<br />
Router Subinterface Configuration (F3-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788525628465-031994f1-b11b-4831-80ce-88081154524c.png" alt="Router Subinterface Config" />
<img src="https://www.image2url.com/r2/default/images/1788525706952-7429f76b-444f-4270-af92-0716ab2e240b.png" alt="Router Subinterface Config" />
<br />
<br />
Router IP Addressing (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788526188221-31a4771c-c9a3-4f01-947b-41e9c3effe9e.png" alt="Router IP Addressing" />
<br />
<br />
Router IP Addressing (F2-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788526734766-34a51a29-4810-4662-a310-31ddefffc64e.png" alt="Router IP Addressing" />
<br />
<br />
Router IP Addressing (F3-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788526470395-2fd86980-b19b-42b1-8b4d-79c2b0f7dace.png" alt="Router IP Addressing" />
<br />
<br />
Router Routing Protocol Configuration (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788527378785-352bd330-8bc4-4052-9131-d88668c10152.png" alt="Routing Protocol Config" />
<br />
<br />
Router Routing Protocol Configuration (F2-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788527741375-0c9df51c-730e-40ac-a20f-5b53fa1842aa.png" alt="Routing Protocol Config" />
<br />
<br />
Router Routing Protocol Configuration (F3-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788527596136-89fb6d10-c509-45fd-a70e-fdccd3be303e.png" alt="Routing Protocol Config" />
<br />
<br />

### Objective

Configure a multi-floor hotel network so each department VLAN can communicate internally, receive DHCP addresses, connect to Wi‑Fi, and route between floors through router-on-a-stick and RIP. This SOP walks a team member through switch, router, DHCP, trunking, and verification tasks in the correct order.

SOP: Configure a Multi-Floor Hotel Network with VLANs, DHCP, Wireless Access, Switchport Access, IP Addressing, Subinterfaces, Encapsulation DOT, Default-Gateways, Trunk Interfaces, Router-On-A-Stick, Routing Protocols (RIP) & Clock Rates


### Key Steps

**1. Create and name VLANs on Floor 1 switch** 

- Log in to **Switch 1 (F1 / Floor 1 switch)**.
- Enter global configuration mode.
- Create the required VLANs and assign clear names: 
  - **VLAN 80** → `reception`
  - **VLAN 70** → `store`
  - **VLAN 60** → `logistics`
- Verify the VLANs were created with `show vlan`.
- Confirm the VLAN list matches the intended department layout before moving on.

 

**2. Assign Floor 1 access ports to the correct VLANs** 

- Identify which end devices are connected to each switch port.
- Put the connected ports into **access mode**.
- Assign ports to the correct VLANs: 
  - **Fa0/1** → VLAN 80 (Reception)
  - **Fa0/2** → VLAN 70 (Store)
  - **Fa0/3** → VLAN 60 (Logistics)
  - **Fa0/4–Fa0/5** → VLAN 80 (Reception)
- Re-run `show vlan` to confirm the ports appear under the correct VLANs.
- Check link lights / topology status to ensure ports are active.

 

**3. Repeat VLAN and access-port setup on Floor 2 switch** 

- Log in to **Switch 2 (F2 / Floor 2 switch)**.
- Identify connected end devices and ports.
- Put ports **Fa0/1–Fa0/5** into **access mode**.
- Create and name VLANs: 
  - **VLAN 50** → `finance`
  - **VLAN 40** → `HR`
  - **VLAN 30** → `sales`
- Assign access ports to the correct VLANs: 
  - **Fa0/1** → VLAN 50
  - **Fa0/2** → VLAN 40
  - **Fa0/3** → VLAN 30
  - **Fa0/4–Fa0/5** → VLAN 40
- Verify with `show vlan` that all VLANs and ports are correct.

 

**4. Repeat VLAN and access-port setup on Floor 3 switch** 

- Log in to **Switch 3 (F3 / Floor 3 switch)**.
- Identify connected devices and ports using interface checks if needed.
- Create and name VLANs: 
  - **VLAN 10** → `IT`
  - **VLAN 20** → `admin`
- Assign ports to VLANs: 
  - **Fa0/1** → VLAN 20
  - **Fa0/2** → VLAN 10
  - **Fa0/3–Fa0/5** → VLAN 10
- Confirm the VLAN-to-port mapping with `show vlan`.
- Make sure the access point and other end devices are placed in the intended VLANs.

 

**5. Configure trunk links from each switch to its router** 

- On each switch, identify the uplink interface connected to the router.
- Set the router-facing switch port to **trunk mode**.
- Apply trunking on: 
  - Floor 1 switch uplink
  - Floor 2 switch uplink
  - Floor 3 switch uplink
- Verify trunk configuration with `show run` or equivalent interface checks.
- Remember: the switch side may show the link as down until the router side is enabled.

 

**6. Enable router interfaces connected to the switches** 

- Log in to each router.
- Identify the interfaces connected to the switches.
- Apply `no shutdown` to the router-facing interfaces.
- Confirm the interfaces transition from down to up.
- If a link remains down, verify both ends of the connection are configured and physically connected correctly.

 

**7. Configure DCE serial clock rate on the required routers** 

- Check which serial interface is marked **DCE**.
- Apply the required **clock rate** on the DCE side.
- Use the same clock rate value shown in the transcript: **64000**.
- Apply this only on routers with DCE serial interfaces (Floor 1 and Floor 2 in this topology).
- Verify with `show controller serial` that the DCE side is correct and the clock rate is set.

 

**8. Build DHCP pools for Floor 1 VLANs** 

- On the Floor 1 router, enable the **DHCP service**.
- Create DHCP pools for each VLAN/subnet: 
  - **reception** for VLAN 80
  - **store** for VLAN 70
  - **logistics** for VLAN 60
- For each pool, define: 
  - Network/subnet
  - Default gateway (router IP for that subnet)
  - DNS server
  - Domain name
- Verify the DHCP pools with `show run`.
- Ensure the pool names match the department names for easier troubleshooting.

 

**9. Configure router subinterfaces for Floor 1 router-on-a-stick** 

- On the Floor 1 router, create subinterfaces on the trunk-facing physical interface.
- Use **802.1Q encapsulation** for each VLAN.
- Create subinterfaces for the VLANs used on Floor 1.
- Assign each subinterface the correct gateway IP address for its VLAN.
- Add descriptions to each subinterface so the purpose is obvious to future technicians.
- Remove any incorrect or unused subinterface entries if created in error.
- Re-check the configuration with `show run` and confirm encapsulation is correct.

 

**10. Test DHCP and Wi‑Fi connectivity on Floor 1** 

- On each end device in the Floor 1 VLANs, request an IP address via **DHCP**.
- Confirm each device receives a valid IPv4 address in the correct subnet.
- Configure the access point with: 
  - An **SSID** for the hotel Wi‑Fi
  - A **WPA2-PSK** password
- Connect a wireless client to the SSID.
- Verify the wireless client receives an IP address and can connect successfully.
- Ping devices within and across the local VLANs to confirm internal connectivity.

 

**11. Configure DHCP and subinterfaces on Floor 2 router** 

- On the Floor 2 router, enable the **DHCP service**.
- Create DHCP pools for the Floor 2 VLANs: 
  - VLAN 50 → finance
  - VLAN 40 → HR
  - VLAN 30 → sales
- For each pool, configure: 
  - Network
  - Default gateway
  - DNS server
  - Domain name
- Configure router subinterfaces for the VLANs using **802.1Q encapsulation**.
- Assign each subinterface the correct gateway IP address.
- Add descriptions to keep the configuration readable and maintainable.
- Verify the setup with `show run` and DHCP tests.

 

**12. Verify Floor 2 DHCP and inter-VLAN communication** 

- Request DHCP addresses from all Floor 2 end devices.
- Confirm each device receives a successful DHCP lease.
- Ping devices within the same floor/VLAN group.
- Ping across VLANs on the same floor to confirm router-on-a-stick is working.
- If a device fails to receive an address, re-check the pool network, gateway, and subinterface configuration.

 

**13. Configure DHCP and subinterfaces on Floor 3 router** 

- On the Floor 3 router, enable the **DHCP service**.
- Create DHCP pools for the Floor 3 VLANs: 
  - VLAN 10 → IT
  - VLAN 20 → admin
- Configure each pool with: 
  - Network
  - Default gateway
  - DNS server
  - Domain name
- Create the router subinterfaces for the VLANs.
- Apply **802.1Q encapsulation** and assign the correct gateway IPs.
- Use descriptions to document the purpose of each subinterface.
- Verify the configuration with `show run`.

 

**14. Test Floor 3 DHCP and local VLAN communication** 

- Request DHCP addresses on Floor 3 end devices.
- Confirm the devices receive valid IP addresses.
- Ping devices within the IT and admin VLANs.
- Confirm local VLAN communication works before moving to inter-network routing.
- If DHCP fails, verify the pool, gateway, and subinterface settings.

 

**15. Assign IP addresses to router serial interfaces** 

- Determine the serial links between routers.
- Assign static IP addresses to each serial interface that is up.
- Use a **/30 subnet mask** for point-to-point serial links.
- Ensure each serial link has only two usable addresses.
- Verify the interface addressing with `show ip interface brief`.
- Confirm the serial links are up on both ends.

 

**16. Enable CDP and verify router neighbors** 

- Enable **CDP** if it is required for discovery and troubleshooting.
- Use CDP to identify connected neighbors and their interfaces.
- Run neighbor commands to confirm which local ports connect to which remote ports.
- Use detailed neighbor output to capture IP addresses and interface mappings.
- Treat CDP as a troubleshooting aid and consider security implications before leaving it enabled in production.

 

**17. Configure RIP v2 on all routers** 

- Enable **RIP version 2** on each router.
- Advertise all directly connected networks.
- Include the serial transit networks and the VLAN subnet networks behind each router.
- Repeat the process on every router so all networks are shared across the topology.
- Verify learned routes with `show ip route rip`.
- Confirm the routing table contains the expected RIP entries.

 

**18. Validate end-to-end routing across the hotel network** [

- Test communication between devices on different floors and VLANs.
- Ping across subnets to confirm routing is working end to end.
- Verify that DHCP, trunking, subinterfaces, serial links, and RIP are all functioning together.
- If a ping fails, troubleshoot in this order: 
  - Physical link status
  - VLAN assignment
  - Trunk configuration
  - Subinterface encapsulation/IP addressing
  - DHCP pool settings
  - Serial interface IPs and clock rate
  - RIP advertisements

### Cautionary Notes

- Always verify the correct VLAN before assigning a port.
- Router interfaces are often **shutdown by default**; remember to apply `no shutdown`.
- Make sure the **DCE side** of a serial link has the correct clock rate.
- Subinterfaces must use the correct **802.1Q VLAN ID** and gateway IP.
- DHCP pools must match the subnet, default gateway, and DNS settings exactly.
- If a link is down, check both ends of the connection, not just one side.
- Use CDP carefully in production environments because it can expose network details.
- Double-check all configurations with `show vlan`, `show run`, `show ip interface brief`, and `show ip route rip` before closing the task.

### Tips for Efficiency

- Use `interface range` to configure multiple switch ports at once.
- Keep VLAN names and DHCP pool names consistent with department names.
- Add descriptions to subinterfaces to simplify future troubleshooting.
- Verify each phase before moving to the next: VLANs, trunks, DHCP, routing, then testing.
- Use `show` commands frequently to catch mistakes early.
- Standardize subnetting and naming conventions across all floors.
- Test with one device first, then validate the rest once the configuration is confirmed.

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
