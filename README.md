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
VLAN & Switchport Configuration F4-SW (IT):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790664149166-2824ed89-cece-4b24-8b3e-064695e3aa77.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790664275065-ebae3087-f515-4383-a79a-42db8059db7f.png" alt="Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration F4-SW (SRV):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790664581779-5548c7d7-b867-4684-984d-3dfe252d2a33.png" alt="Switchport Configuration" />
<br />
<br />
<img src="https://www.image2url.com/r2/default/images/1790664664442-e9c656e5-728d-4003-b0d7-e005211f9c5d.png" alt="Switchport Configuration" />
<br />
<br />
Server Configuration:  <br/>
<br />
<img src="https://www.image2url.com/r2/default/images/1790694624925-2e421300-b808-4e89-9ef8-fc8cb7171ce5.png" alt="SRV Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790695088656-c0222b22-9321-4dee-983a-bd024dec3b55.png" alt="SRV Configuration" />
<br />
<br />
Switchport Configuration F1-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790695319409-9d79baad-c2ed-40dc-92cf-492243dfeea6.png" alt="MLS Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790696429398-4e095c47-08af-4b3f-b165-3b614f79c9e9.png" alt="IP Routing & No Switchport" />
<img src="https://www.image2url.com/r2/default/images/1790696622742-f26005ac-0178-41d3-b8ea-89030c2d158a.png" alt="Static IP Address" />
<br />
<br />
Switchport Configuration F2-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790695534042-b7dfcb61-7e51-45ec-bbca-e8c70dc6e720.png" alt="MLS Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790696767656-369caf82-70da-4103-95ed-9707d5ace4c8.png" alt="IP Routing, No Switchport & Static Addressing" />
<br />
<br />
Router Configuration (F1-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790697679955-c5cc3c04-a06a-4aec-ab95-f84803edf13f.png" alt="IP Addressing" />
<img src="https://www.image2url.com/r2/default/images/1790697974917-cd579312-e89e-47f5-bae5-95288f7fd6b5.png" alt="Clock Rate Check" />
<img src="https://www.image2url.com/r2/default/images/1790698274281-b2d0ef49-f0f0-46ea-9dc2-d3ff082c9b39.png" alt="Clock Rate Set" />
<img src="https://www.image2url.com/r2/default/images/1790753608197-8cd7259b-8af3-4389-b187-d419b4d8b0d8.png" alt="IP Validation Check & Interface No Shut" />
<img src="https://www.image2url.com/r2/default/images/1790754322060-01440d80-7b9e-4a63-93e8-bfa19cd89379.png" alt="Interface No Shut" />
<br />
<br />
Router Configuration (F2-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790698703501-84b735f3-d7a7-41a7-a912-960db47d7b11.png" alt="IP Addressing" />
<img src="https://www.image2url.com/r2/default/images/1790751796226-a9093880-a010-43c7-8666-9385c8e341f5.png" alt="Clock Rate Check" />
<img src="https://www.image2url.com/r2/default/images/1790752001322-aacb86fc-a77e-4314-93bf-874ab50ed864.png" alt="Clock Rate Set" />
<img src="https://www.image2url.com/r2/default/images/1790752102196-8be87ca6-7c67-49e9-a448-9b8872e0dacd.png" alt="Clock Rate Set" />
<img src="https://www.image2url.com/r2/default/images/1790752562321-f9eb06b9-ee70-488f-bf89-d83b4fc4fb28.png" alt="IP Validation Check" />
<img src="https://www.image2url.com/r2/default/images/1790752954957-b441d7ab-273f-435e-bbf7-d661a63c7394.png" alt="Interface No Shut" />
<br />
<br />
Router Configuration (F3-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790754544856-86c7f497-a2cc-4d41-86d6-99b2083ccea6.png" alt="IP Addressing" />
<img src="https://www.image2url.com/r2/default/images/1790756199023-4012dd9a-768b-487f-9092-788eafacbf69.png" alt="Interface No Shut" />
<br />
<br />
Router Configuration (F4-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790755017806-089ab2f3-c086-4fce-bf11-05fb88c5b1d7.png" alt="IP Addressing" />
<img src="https://www.image2url.com/r2/default/images/1790755179058-33378b86-f67a-4910-90ef-c1503bc09f9e.png" alt="Clock Rate Check" />
<img src="https://www.image2url.com/r2/default/images/1790755280428-7556e20c-53fb-4e72-b189-96d3790e5362.png" alt="Clock Rate Set" />
<img src="https://www.image2url.com/r2/default/images/1790755373473-667f3c3d-9c5b-4b7c-b093-707eed39bc6e.png" alt="IP Addressing" />
<img src="https://www.image2url.com/r2/default/images/1790756359521-ee99a5d1-28ee-400f-a757-348e9439e257.png" alt="Interface No Shut" />
<br />
<br />
Switchport & IP Configuration F3-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790755518159-1fae127e-bd82-44b4-a3c9-e7eb4f382e3e.png" alt="MLS Configuration" />
<br />
<br />
Switchport & IP Configuration F4-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790755933866-5b4bfab5-b2ae-4302-a783-33228b7e5e99.png" alt="MLS Configuration" />
<br />
<br />
Interface Vlan Configuration F1-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790767127868-6067a685-448a-4536-9b5f-caeee7075b61.png" alt="Interface Vlan Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790767415093-86c5460e-83d7-44fa-a40c-e6389fc2d67a.png" alt="Interface Vlan Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790767478781-db5de25a-d972-407a-a82f-153af721a1d1.png" alt="Interface Vlan Configuration" />
<br />
<br />
Interface Vlan Configuration F2-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790776148391-e6255b62-fccb-41ba-9bc2-7cb3837754f9.png" alt="Interface Vlan Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790776220343-4eaddf81-3945-43e5-a8e7-de717201db2a.png" alt="Interface Vlan Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790776476161-bbee8fca-98df-495a-9b56-d3a38919dda8.png" alt="Interface Vlan Configuration" />
<br />
<br />
Interface Vlan Configuration F3-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790776595804-69139d80-b34e-4090-9ff4-39fcdd287996.png" alt="Interface Vlan Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790776880854-6888a715-ffc8-48aa-ab2f-b53864acedab.png" alt="Interface Vlan Configuration" />
<br />
<br />
Interface Vlan Configuration F4-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790777015174-ca4c1d4d-b833-4551-bede-f6ebbf40e9f3.png" alt="Interface Vlan Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790777082996-ec31a3af-92c3-46b8-bd66-e02a561e371c.png" alt="Interface Vlan Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790777150097-dfed2641-65b5-4c83-971f-2b3993b132e1.png" alt="Interface Vlan Configuration" />
<br />
<br />
DHCP-POOL Configuration (DHCP SRV):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790835185944-cbab0344-84df-4298-b6c6-ca406576ec1e.png" alt="DHCP Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790835622774-ad3be878-8ee8-4db3-8c06-18c1a5d620aa.png" alt="DHCP Configuration" />
<br />
<br />
DNS Configuration (DNS SRV):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790841255236-135928f8-eacc-4d5b-8dd4-c69fb7023947.png" alt="DNS Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790841336160-910f09b9-49c5-4176-b509-a57afb551ad2.png" alt="DNS Configuration" />
<br />
<br /> 
Routing Protocol Configuration F1-MLS:  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790777227292-e3b2107c-4a65-4c96-a563-e6e1572c4085.png" alt="EIGRP Configuration" />
<br />
<br />
Routing Protocol Configuration F2-MLS:  <br/> 
<br/> 
<img src="https://www.image2url.com/r2/default/images/1790836419842-fb411adb-0306-4898-a824-6ce42d171b50.png" alt="EIGRP Configuration" />
<br />
<br />
Routing Protocol Configuration (F1-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790836509645-6723c9bd-12b5-4491-8e22-ffc43e3f0c78.png" alt="EIGRP Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790836647718-55c1776e-5f6f-465d-b998-73a201ae6835.png" alt="EIGRP Configuration" />
<br />
<br />
Routing Protocol Configuration (F4-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790836821494-6a237b4e-462b-463d-aa75-5f8062f4d7ef.png" alt="EIGRP Configuration" /> 
<br />
<br />
Routing Protocol Configuration (F2-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790837353663-627d0aaf-593a-44c7-8d73-9630048aab11.png" alt="EIGRP Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790837866769-744d1b31-aee8-400c-a152-b37caf703c08.png" alt="EIGRP Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790838010682-773c3dfe-814c-4332-84d1-5dd37d4873d2.png" alt="Trouble-Shooting" />
- Wrong networks configured were remedied by removing sed networks by prefixing the "NETWORK" command with the word "NO"
<br />
<br />
Routing Protocol Configuration (F3-Router):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790838281587-4393f7fd-4e4b-4532-a732-a42cf9295dbf.png" alt="EIGRP Configuration" />
<br />
<br />
Routing Protocol Configuration (F3-MLS):  <br/> 
<br/>
<img src="https://www.image2url.com/r2/default/images/1790838398200-306ab350-f626-49b3-ac6d-61cfef86a55d.png" alt="EIGRP Configuration" />
<br />
<br />
Routing Protocol Configuration (F4-MLS):  <br/> 
<br/>
<img src="https://www.image2url.com/r2/default/images/1790838652076-52e882f6-3e4b-48c0-8e44-246f67be4586.png" alt="EIGRP Configuration" />
<br />
<br />
IP DHCP-HELPER ADDRESS (F1-MLS & F2-MLS):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790839766888-5c23dfa5-bde1-4e0b-96bc-5157f316cce0.png" alt="IP Helper-Address Configuration" />
<br />
<br />
IP DHCP-HELPER ADDRESS (F3-MLS & F4-MLS):  <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790840435303-dce1f831-5b23-4c02-8b03-e4a42cc8067d.png" alt="IP Helper-Address Configuration" />
<img src="https://www.image2url.com/r2/default/images/1790840566065-7c0f5d12-fc25-45a4-be93-4d6bdc120eae.png" alt="IP Helper-Address Configuration" /> 
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
