# MPLS-Auto-BW-Junos

## Executive Summary
RSVP traffic engineering (TE) capabilities are so enriched that it would require a lengthy book to cover all the TE capabilities.  One of very attractive feature of rsvp singled Label Switch Path (LSP) is to signal or reserve bandwidth across the physical links through which LSP traverses and to avoid links over subscription during LSP setup rsvp also offers a feature to subscribe links bandwidth out of total bandwidth. Static bandwidth for LSPs does not suit production network as production network traffic patrons are not always static. So, LSP signaled with static bandwidth configuration as it does not cater dynamic bandwidth adjustments which is often required due to increase or decrease in traffic volume. Auto-bandwidth provides capability to adjust LSP bandwidth signaling based on traffic needs.  In this document I will endeavor to cover RSVP auto-bandwidth capabilities and how it can help to optimally utilise rsvp enabled links in MPLS backbone network. 

All of LSP bandwidth signaling , rsvp link subscription is control plane based activities and does not put any restriction on forwarding plane traffic. 

## Lab Topology 
![Lab_Topology]()