# SD-WAN in Azure

🤔Are you considering extending your SDWAN reachability towards Azure? 
 
🎉Good news – it’s definitely possible and a lot of customers are already doing it! Whether you run a Hub & Spoke or a virtual WAN environment, there are three main approaches to consider👇 

##

1️⃣ 𝐌𝐚𝐧𝐚𝐠𝐞𝐝 𝐒𝐃𝐖𝐀𝐍 𝐢𝐧 𝐯𝐢𝐫𝐭𝐮𝐚𝐥 𝐖𝐀𝐍 offers a solution for extending your SDWAN overlay directly into Azure, up to virtual SDWAN appliances integrated 𝘯𝘢𝘵𝘪𝘷𝘦𝘭𝘺 inside the virtual hub. This option is available for virtual WAN topologies only. 

&emsp;&emsp;https://learn.microsoft.com/en-us/azure/virtual-wan/sd-wan-connectivity-architecture#direct

&emsp;&emsp;[List of supported partners](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-locations-partners#partners-with-integrated-virtual-hub-offerings)

&emsp;&emsp;[Throughput considerations and underlay options](https://techcommunity.microsoft.com/t5/azure-networking-blog/managed-sd-wan-in-vwan-throughput-considerations-and-underlay/ba-p/4097864)

2️⃣ 𝐕𝐌-𝐬𝐞𝐫𝐢𝐞𝐬 𝐝𝐞𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭𝐬 also allow to stretch the SDWAN overlay up to virtual SDWAN appliances, here within your customer-managed VNet. This solution requires 𝘮𝘢𝘯𝘶𝘢𝘭 𝘥𝘦𝘱𝘭𝘰𝘺𝘮𝘦𝘯𝘵 and leverages BGP endpoint in virtual WAN, or the Azure Route Server (ARS) in Hub & Spoke, for dynamic route exchange. Depending on the complexity of your addressing plan, static routing may also be possible.

&emsp;&emsp;https://learn.microsoft.com/en-us/azure/architecture/networking/guide/sdwan-integration-in-hub-and-spoke-network-topologies

&emsp;&emsp;https://github.com/adstuart/azure-sdwan?tab=readme-ov-file#option-6---virtual-wan-v3-bgp-endpoint--nva

&emsp;&emsp;https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-bgp-peering-hub

 
3️⃣ Finally, the 𝐜𝐥𝐨𝐮𝐝 𝐞𝐝𝐠𝐞 𝐜𝐨𝐥𝐨 𝐦𝐨𝐝𝐞𝐥 uses physical SDWAN appliances in the cloud edge PoP to terminate the SDWAN overlay, providing 𝘥𝘪𝘳𝘦𝘤𝘵 𝘤𝘰𝘯𝘯𝘦𝘤𝘵𝘪𝘷𝘪𝘵𝘺 𝘵𝘰 𝘈𝘻𝘶𝘳𝘦 via ExpressRoute, for instance.

&emsp;&emsp;https://github.com/adstuart/azure-sdwan?tab=readme-ov-file#option-7---cloud-edge-colocation-physical-appliance

&emsp;&emsp;https://learn.microsoft.com/en-us/azure/virtual-wan/sd-wan-connectivity-architecture#hybrid

##

Don't miss out on the benefits of SDWAN in Azure and start exploring your options today! 🗺️💫

##
- 🎨Image created using Microsoft Designer
- [LI post](https://www.linkedin.com/posts/cynthia-treger-6663402_microsoft-azure-azurenetworking-activity-7171210708481748994-MENa?utm_source=share&utm_medium=member_desktop)
