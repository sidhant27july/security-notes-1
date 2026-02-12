Palo Alto Packet Flow (Inside → Outside)
Step-by-Step Flow
User → Interface → Zone → Policy → App-ID →
Content Inspection → NAT → Routing → Egress

Diagram
[User PC]
    |
    v
[Ingress Interface]
    |
[Zone Check]
    |
[Security Policy]
    |
[App-ID Identification]
    |
[Threat / URL / AV]
    |
[NAT]
    |
[Routing Table]
    |
[Outside Interface]

Important Palo Alto Interview Point

Policy is checked before App-ID

App-ID can change after initial packets

Policy is re-evaluated if App-ID changes



