# HOME-NETWORK-DIAGRAM
HOME NETWORK DIAGRAM

The purpose of the diagram.
* The purpose of this project is to identify all devices ,IP addresses and protocols they use on my Home network

How you discovered devices and protocols.
* I discovered some of the devices by using fing,ipconfig, ARP, device settings

What the SOC annotations reveal (trust boundaries, attack surface, blind spots).

What you would do differently if this were an enterprise network (network segmentation, NAC, 802.1X, logging everywhere).

This becomes a reusable document you can link in your resume or talk about in interviews.



TO BE ANSWERED IN FEW MONTHS TIME

The biggest gap: SOC analyst annotations (the “so what?”)
Right now the diagram is a network inventory. To impress a SOC manager, you need to show you understand threat modelling, visibility, and attack surface. Add a second version (or annotate this one with coloured callouts) covering:

Trust boundary – Red dashed line between Internet and router, labelled “External/Internal Trust Boundary”.

External attack surface – Circle the router’s public-facing side and note: “Unknown open ports (no admin access) – possible SSH/HTTP admin exposed?”

Critical assets – Put a star next to your laptop and phone. Those hold your personal data; if compromised, impact is highest.

Visibility gaps – Add a note: “No east‑west traffic logs – lateral movement between devices would be invisible. ARP table provides only partial host discovery.”

Lateral movement risk – Show with a dashed arrow: if one device is compromised, attacker can reach any other device because there’s no internal segmentation.

Logging opportunities – Mark endpoints where you could install a SIEM agent (e.g., on your laptop) and note that router logs are unavailable.

These additions take the diagram from “I drew my network” to “I analysed my network like a defender.”

NEXT STEPS

Suggested next steps
Create a “Version 2” of the diagram incorporating the layout fixes and all the SOC annotations. Use a different background colour for the callout notes so they stand out (e.g., light blue or red for security notes).

Export both versions as PNG. V1 (current) can be the clean inventory; V2 is the annotated security analysis.

Write a short README.md that explains what you did, why you added each annotation, and what you’d do differently in an enterprise. (I can help draft this when you’re ready.)

Upload V2 when done and I’ll review it again.

You’ve already done the hard part — discovering devices and mapping them. Now let’s layer on the analyst mindset that will make employers take notice.

Would you like me to sketch a quick ASCII layout suggestion for how to group the devices, or do you want to jump straight into making V2?
