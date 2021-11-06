##  What are the NS IP addresses for Google, Facebook and Tesla? 


### Google Ns IP Address

| Nameserver     | Ipv4 address  |
| :------------- | :------------ |
| ns1.google.com | 216.239.32.10 |
| ns2.google.com | 216.239.34.10 |
| ns3.google.com | 216.239.36.10 |
| ns4.google.com | 216.239.38.10 |


### Facebook Nslookup IP Address

| Nameserver        | Ipv4 address  |
| :---------------- | :------------ |
| a.ns.facebook.com | 129.134.30.12 |
| b.ns.facebook.com | 129.134.31.12 |
| c.ns.facebook.com | 185.89.218.12 |
| d.ns.facebook.com | 185.89.219.12 |

### Tesla Nslookup IP Address

| Nameserver           | Ipv4 address  |
| :------------------- | :------------ |
| edns69.ultradns.biz. | 204.74.67.69  |
| edns69.ultradns.com. | 204.74.66.69  |
| edns69.ultradns.net. | 204.74.110.69 |
| edns69.ultradns.org. | 204.74.111.69 |
| a1-12.akam.net       | 193.108.91.12 |
| a7-66.akam.net       | 23.61.199.66  |
| a9-67.akam.net       | 184.85.248.67 |
| a10-67.akam.net      | 96.7.50.67    |
| a12-64.akam.net      | 184.26.160.64 |
| a28-65.akam.net      | 95.100.173.65 |
                           
 


### Breakdown the following RFC 191|8 IPv4 address range into exactly 4 subnets with no address.

* 10.10.10.0
* 192.168.0.0
* 172.168.1.0



                                                10.10.10.0
                            All 4 of the Possible /10 Networks for 10.10.10
| Network ID | CIDR  |         Host ID Range          | Number of Usable Host | Broadcast ID   |
| :--------- | :---: | :----------------------------: | :-------------------: | :------------- |
| 10.10.10.0 |  /10  |   10.0.10.1 - 10.62.255.254    |          62           | 10.63.255.255  |
| 10.64.0.0  |  /10  |  10.64.10.65 - 10.126.255.254  |          62           | 10.127.255.255 |
| 10.128.0.0 |  /10  | 10.128.10.129 - 10.191.255.254 |          62           | 10.191.255.255 |
| 10.192.0.0 |  /10  | 10.192.10.193 - 10.254.255.254 |          62           | 10.255.255.255 |


                                                172.168.1.0
                            All 4 of the Possible /18 Networks for 172.168.1
| Network ID    | CIDR  |         Host ID Range         | Number of Usable Host | Broadcast ID    |
| :------------ | :---: | :---------------------------: | :-------------------: | :-------------- |
| 172.168.0.0   |  /18  |  172.168.0.1 - 172.168.1.254  |          62           | 172.168.63.255  |
| 172.168.64.0  |  /18  | 172.168.65.1 - 172.168.1.254  |          62           | 172.168.127.255 |
| 172.168.128.0 |  /18  | 172.168.129.1 - 172.168.1.254 |          62           | 172.168.191.255 |
| 172.168.192.0 |  /18  | 172.168.193.1 - 172.168.1.254 |          62           | 172.168.255.255 |


                                                192.168.0.0
                            All 4 of the Possible /26 Networks for 192.168.0
| Network ID    | CIDR  |         Host ID Range         | Number of Usable Host | Broadcast ID  |
| :------------ | :---: | :---------------------------: | :-------------------: | :------------ |
| 192.168.0.0   |  /26  |  192.168.0.1 - 192.168.0.62   |          62           | 192.168.0.63  |
| 192.168.0.64  |  /26  | 192.168.0.65 - 192.168.0.126  |          62           | 192.168.0.127 |
| 192.168.0.128 |  /26  | 192.168.0.129 - 192.168.0.190 |          62           | 192.168.0.191 |
| 192.168.0.192 |  /26  | 192.168.0.193 - 192.168.0.254 |          62           | 192.168.0.255 |