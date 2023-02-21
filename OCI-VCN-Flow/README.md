## Widget description of `vcn_flow_logs_2.json` file


1. VCN Flows [30m]
	Shows the number of VCN Flows for the last 30 minutes.
	This will show the overview of the network traffic in your VCN.

2. Bytes Out [30m]
	Shows the number of bytes out from the VCN network.
	This will show the overview of the network traffic in your VCN.
	`data.bytesOut`: This field provides the number of bytes sent out by the source.
	This information can be used to determine the amount of data that was transmitted by a particular source in the network flow.
	By analyzing the number of bytes transferred in a flow, you can gain insights into the amount of data that was transferred and the behavior of your applications and services. For example, if you notice a high number of bytes transferred in a particular flow, it could indicate a data-intensive application or service that is generating significant network traffic. This information can be used to optimize network performance, troubleshoot issues, and identify potential security threats.

3. Packets Transferred [30m]
	`data.packets` refer the number of packets transmitted in the flow. 
	This can be used to track overall network activity, or to monitor the behavious of a specific host or applications.
	A packet is a unit of data that is transmitted over a network, and it contains information such as the source and destination IP addresses, the protocol used, and the payload data.
	By analyzing the number of packets transferred in a flow, you can gain insights into the amount of data that was transferred and the behavior of your applications and services. For example, if you notice an unusually high number of packets for a particular flow, it could indicate a potential DDoS attack or a misconfigured application that is generating excessive network traffic.
	
	GRAPH: tracks the overall volume of network traffic.


4. Trafffic by protocol
	Represents the protocol used by the flow.
	Example: ICMP(Internet Control Message Protocol), TCP(Transmission Control Protocol) and UDP(User Datagram Protocol).
	By analyzing the `data.protocol` field, you can gain insight into the types of traffic that are flowing through your network. This information can be useful for troubleshooting network issues, identifying potential security threats, and optimizing network performance.


5. Request Status of VCN Flows
	This field represents the status of the flow, such as "OK" or "REJECT". You could use this value to monitor the number of rejected flows over time.

6. Actions Taken 
	`data.action` represents the action on the flow by a network security rule or policy.
	Can have values like:
	- "ACCEPT": The flow was allowed to proceed.
	-   "DROP": The flow was silently dropped, with no notification sent to either the source or destination of the flow.
	-   "REJECT": The flow was rejected, and a notification was sent to the source of the flow indicating that the flow was not allowed to proceed.
	-   "LOG": The flow was logged, but no action was taken on it.
	This field can be useful for monitoring security policy violations and identifying potential security threats. For example, if you see a large number of flows being rejected by a security policy, you may want to investigate the source of those flows to determine whether they represent a potential security threat.

7. Flow by Source Address Heatmap
	Shows the amount of data which is flowing from a source address.

8. Top Talkers Heatmap
	This table identifies the top talkers in your VCN, showing the source and destination IP addresses that have the most traffic. This table identifies the top talkers in your VCN, showing the source and destination IP addresses that have the most traffic. 
	It shows the bytes being transferred between source and destination addresses.
	The Top Talkers graph provides valuable insights into the behavior of your applications and services, allowing you to identify which IP addresses are generating the most traffic in your VCN. This information can be used to optimize network performance, troubleshoot issues, and identify potential security threats. For example, if you notice an unusual amount of traffic coming from a particular IP address, it could indicate a compromised system or a potential DDoS attack, and you may need to investigate further.
	
	
---

---

> Each flow log line in OCI VCN flow logs contains a set of data fields that provide information about the network traffic for a particular flow. These fields include the source and destination IP addresses, the protocol used, the source and destination ports, the number of bytes transferred, and the number of packets transferred.

These are some of the widgets that OCI provide in their dashboards:

1.  `Flow Logs Overview Graph`: This graph provides an overview of the network traffic in your VCN, including the number of flows, packets, and bytes for both inbound and outbound traffic.
2. `Top Talkers Graph`: This graph identifies the top talkers in your VCN, showing the source and destination IP addresses that have the most traffic. This graph identifies the top talkers in your VCN, showing the source and destination IP addresses that have the most traffic. To create the Top Talkers graph, OCI analyzes the flow logs to identify the source and destination IP addresses for each flow. Then, it aggregates the flows by IP address and calculates the total number of packets and bytes transferred between each pair of IP addresses. Finally, it sorts the results by the amount of traffic and displays the top talkers in descending order. The Top Talkers graph provides valuable insights into the behavior of your applications and services, allowing you to identify which IP addresses are generating the most traffic in your VCN. This information can be used to optimize network performance, troubleshoot issues, and identify potential security threats. For example, if you notice an unusual amount of traffic coming from a particular IP address, it could indicate a compromised system or a potential DDoS attack, and you may need to investigate further.
3. `Traffic by Protocol Graph`: This graph shows the breakdown of traffic by protocol, such as TCP, UDP, or ICMP. OCI analyzes the flow logs to identify the protocol used for each flow. It then aggregates the flows by protocol and calculates the total number of packets and bytes transferred for each protocol. Finally, it displays the results in a bar chart, with each bar representing a different protocol and the height of the bar indicating the amount of traffic. The Traffic by Protocol graph provides valuable insights into the types of traffic that are flowing in and out of your VCN. For example, if you notice that a large percentage of the traffic is using the TCP protocol, it could indicate that a lot of data is being transferred between applications, while a high number of ICMP packets could indicate network connectivity issues. This information can be used to optimize network performance, troubleshoot issues, and identify potential security threats, such as an unusual amount of traffic using an uncommon or unauthorized protocol.
4. `Traffic by Port Graph`: This graph shows the breakdown of traffic by port, allowing you to identify which ports are being used the most.
5. `Security Rule Effectiveness Graph`: This graph shows the effectiveness of your security rules by displaying the number of allowed and denied flows.
6. `Time Series Graph`: This graph displays the network traffic over time, allowing you to identify trends and patterns.
These dashboard graphs provide a comprehensive view of your VCN network traffic and allow you to quickly identify potential security issues, optimize network performance, and gain insights into the behavior of your applications and services.
	
	
	
	
	
	
	
