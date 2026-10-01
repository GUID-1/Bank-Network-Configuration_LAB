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
DHCP SRV Configuration <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790849414766-b2ad513e-3117-4d4e-993b-4ff4bf6d4c04.png" alt="DHCP SRV Configuration" />
<br/>
<br/>
DNS SRV Configuration <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790849161656-9930d4c1-6f30-4224-b395-7da1e5ec2e21.png" alt="DNS SRV Configuration" />
<br/>
<br/>
HTTPS SRV Configuration <br/>
<br/>
<img src="https://www.image2url.com/r2/default/images/1790849332268-1f292c30-23a0-4c9b-ae37-2841369d3c48.png" alt="HTTPS SRV Configuration" />
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


