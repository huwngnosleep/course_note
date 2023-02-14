https://www.coursera.org/learn/cloud-computing/lecture/mKf5m/2-napster

Servers and Clients
- Server store metadata about which file in which client
- Client store the file on its own

When a query coming, servers communicate with each others and get a list of all available clients containing that file (TCP) 

When a new peer join to system, there is a server keeps recently joined node and send new peers neighbor table

Problems:
- Centralized servers -> bottle neck
- No security (messages are plain text)