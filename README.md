# -Configure-and-test-basic-firewall-rules-to-allow-or-block-traffic.
 Documented Steps Used
Used Windows Defender Firewall with Advanced Security.

Created inbound rule to block TCP port 23.

Tested using telnet.

Deleted rule to restore firewall to original state
 
 Summary: How Firewalls Filter Traffic
Firewalls act as gatekeepers, monitoring and controlling network traffic based on defined rules. They can:

Allow or block traffic based on IP address, port, or protocol.

Filter inbound (coming into the device) or outbound (going out from the device) traffic.

Protect against unauthorized access and reduce attack surfaces.

Be host-based (like Windows Firewall or UFW) or network-based (like a hardware firewall/router).

