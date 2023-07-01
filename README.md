Web infrastructure design

    Network basics
    Server
    Web server
    DNS
    Load balancer
    Monitoring
    What is a database
    What’s the difference between a web server and an app server?
    DNS record types
    Single point of failure
    How to avoid downtime when deploying new code
    High availability cluster (active-active/active-passive)
    What is HTTPS
    What is a firewall

1.  Network basics involve essential concepts in computer networking, such as nodes (connected devices), links (connections between nodes), protocols (data transmission rules), IP addressing (unique device identification), routers and switches (network devices), network topologies (arrangement of devices), LAN and WAN (local and wide area networks), security measures (firewalls), DNS (domain name translation), and troubleshooting.

2.  A server is a computer or system that provides resources and services to other devices over a network. It handles client requests for files, data, applications, or tasks. Examples include file servers, web servers, application servers, database servers, mail servers, print servers, DNS servers, and proxy servers. Servers are powerful, reliable, and dedicated to delivering efficient performance.

3.  A web server is a computer or software that hosts websites and delivers web pages to clients over the internet using the HTTP protocol.

4.  DNS (Domain Name System) is a system that translates human-readable domain names (e.g., www.example.com) into corresponding IP addresses, enabling devices to locate and communicate with each other on the internet.

5.  A load balancer is a device or software that distributes incoming network traffic across multiple servers or resources to ensure efficient utilization and improved performance. It helps evenly distribute workloads, optimize resource allocation, and enhance the reliability and scalability of systems or applications.

6.  Monitoring is the ongoing process of observing and tracking the performance and availability of computer systems, networks, applications, or services to ensure they are working properly.

7.  A database is a structured collection of data stored on a computer. It allows for efficient organization, retrieval, modification, and analysis of information.

8.  A web server hosts and delivers web pages and content, while an application server executes dynamic applications with advanced features and supports complex functionalities.

9.  DNS (Domain Name System) uses various record types to store and provide different types of information. Here are some commonly used DNS record types:

        A Record: Maps a domain name to an IPv4 address.
        AAAA Record: Maps a domain name to an IPv6 address.
        CNAME Record: Creates an alias for a domain name.
        MX Record: Specifies mail servers for a domain.
        TXT Record: Stores text-based information.
        NS Record: Identifies authoritative DNS servers.
        PTR Record: Performs reverse DNS lookup.
        SRV Record: Specifies service locations within a domain.
        CAA Record: Specifies allowed certificate authorities.
        SOA Record: Provides zone-related information.

10. A single point of failure is a vulnerable component or system that, if it fails, can cause the entire system to fail. Redundancy and fault-tolerant measures are implemented to mitigate this risk.

11. To avoid downtime when deploying new code:

        Test in a staging environment.
        Use a rolling deployment strategy.
        Employ load balancers.
        Implement feature toggles.
        Automate deployment with CI/CD.
        Monitor for issues.

12. A high availability cluster ensures continuous operation. In active-active, all nodes share the workload. In active-passive, one node handles requests while others are on standby.

13. HTTPS is the secure version of HTTP. It encrypts data transmitted between a web browser and a server, ensuring privacy and preventing unauthorized access.

14. A firewall is a security system that monitors and controls network traffic to protect against unauthorized access and potential threats.
