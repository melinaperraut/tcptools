# tcptools
INFO 314 TCP/IP Tools assignment repository

<h1> Using "ping" </h1>

- What were the min/avg/max/stddev statistics for each?
  - <b>Amazon:</b>
    - Overall stats: Min 10 ms, Avg 10.3 ms, Max 13 ms, Std dev 0.47 ms
    - Ping 1: Min 10 ms, Max 13 ms, Avg 10 ms
    - Ping 2: Min 10 ms, Max 13 ms, Avg 11 ms
    - Ping 3: Min 10 ms, Max 11 ms, Avg 10 ms
  - <b>Google:</b> 
    - Overall stats: Min 10 ms, Avg 12.3 ms, Max 23 ms, Std dev 1.25 ms
    - Ping 1: Min 10 ms, Max 19 ms, Avg 12 ms
    - Ping 2: Min 10 ms, Max 12 ms, Avg 11 ms
    - Ping 3: Min 10 ms, Max 23 ms, Avg 14 ms
  - <b>Microsoft:</b> 
    - Overall stats: Min 9 ms, Avg 10 ms, Max 14 ms, Std dev 0 ms
    - Ping 1: Min 10 ms, Max 10 ms, Avg 10 ms
    - Ping 2: Min 9 ms, Max 14 ms, Avg 10 ms
    - Ping 3: Min 9 ms, Max 12 ms, Avg 10 ms
- Was there any packet loss on any of the pings?
  - No, there was no packet loss on any of the pings for any of the sites.
- Did the IP address change for a given website between pings?
  - <b>Amazon:</b> Yes, the IP address changed between each ping.
  - <b>Google:</b> No, the IP address did not change between any of the pings.
  - <b>Microsoft:</b> No, the IP address did not change between any of the pings.

<h1> Using "tracert" </h1>

- What was the target server's IP address?
  - <b>Amazon:</b> 18.65.233.187
  - <b>Google:</b> 142.251.33.100
  - <b>Microsoft:</b> 23.212.181.121
- How many hops were needed to reach the target?
  - <b>Amazon:</b> 17
  - <b>Google:</b> 10
  - <b>Microsoft:</b> 8
- Can you identify your ISP from the intermediate server DNS names?
  - Yes (it is Comcast).
- Identify the "class" of IP address for each major step in the trip
  - <b>Amazon:</b> Class transitions from C (hop 1) to A (hop 2) to B (hop 16) to A (hop 17). Final IP address class is A.
  - <b>Google:</b> Class transitions from C (hop 1) to A (hop 2) to B (hop 8). Final IP address class is B.
  - <b>Microsoft:</b> Class transitions from C (hop 1) to A (hop 2). Final IP address class is A.
