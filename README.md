# Portfolio Images

Hi, I'm a Senior Software Engineer working at [CRSP Center for Research in Security Prices](https://crsp.org). I'm a member of the Market Indexes Software Development team responsible for the systems that produce the data that backs legendary securities like [MGC](https://investor.vanguard.com/investment-products/etfs/profile/mgc) and [VTI](https://investor.vanguard.com/investment-products/etfs/profile/vti#overview). I just completed my first year at CRSP and have been shifting gears toward everything data and finance data. Previous to CRSP I worked at [DSI](https://datascience.uchicago.edu/iot-lab/) Data Science Institute allocated to the Internet Equity Initiative ([IEI](https://internetequity.uchicago.edu/)) as a Backend/Data Engineer. I'm fascinated by the decision-making processes and data-driven visualizations, finance, and product design. I'm known for my previous experience with computer networks leading the full-stack work of [https://beadchallenge.org](https://beadchallenge.org) and [Netrics](http://tigerteam.cs.uchicago.edu).

Instead of a wordy cv/resume, here's a more relaxed collage of images with important documentation of my work as most of it is open source. Disclaimer: some conclusions here are my own. 

<hr />

| Projects                      | Description          |
|-------------------------------|----------------------|
| [![Alt Text](https://github.com/ggmartins/ggmartins/assets/2147779/4ae16569-8578-4131-8f15-949d15729f5e)](https://github.com/ggmartins/ggmartins/assets/2147779/4ae16569-8578-4131-8f15-949d15729f5e) | **Netrics Backend**. [DSI](https://datascience.uchicago.edu). In my responsibility for 3 years, in prod it crossed the 1 billion data-point mark of encrypted data. The stack includes a Golang data collection application, python and terraform IaC, SQL database, parallel Python data ingestion, Kafka producer/consumers. On the right, is the System Design for [https://beadchallenge.org](https://beadchallenge.org)  |

<hr />

![image](https://github.com/ggmartins/ggmartins/assets/2147779/eecf4d41-415c-465e-a19e-be0f16e1401b)
<p align="center">
  Figure 2. Aggregated average latency (active unloaded ICMP) for all Netrics deployed devices in Chicago city. As expected: fiber tech has lower latency compared to the other technologies. Data warehoused on TimescaleDB, image extracted from Superset BI tool. Estimated devices deployed: 120 in Chicago area. We benchmark the internet for ISPs to ensure internet consumers are getting a fair performance from their contracted services and understand any significant differences between regions that are considered to be antagonistic from their socio-economic characteristics.
</p>
<hr />

![image](https://github.com/ggmartins/ggmartins/assets/2147779/8cd6c9cb-3dea-4e09-ac75-9656139882d3)
<p align="center">
  Figure 3. A Netrics Grafana dashboard with fluctuation on both latency and speed test: Negligable from regular users standpoint. Opportunity: Real research questions remain UNANSWERED: <br>(1) Considering wifi may be the bottleneck, do savvy users (high performance multiplay game players, traders, power internet users) even use wifi to begin with? if so, %? (2)
  A drop of 400Mbps (1000Mbps - 600Mbps, due to wifi restrictions or something else) even noticable for regular users beyond rare events such as large gaming downloading? If so, when? Hypothesis: It's negligable.<br>
  (3) Network impairments such as packet drop, high jitter even noticable considering regular internet users experience? How much can they tolerate? 
</p>
<hr />

![image](https://github.com/ggmartins/ggmartins/assets/2147779/e6ac02e7-c2a4-45bb-9368-bcf8222b8f3c)
<p align="center">
  Figure 4. Campus deployment of Netrics, showing high latency for an outlier (Booth School). Image extracted from Looker Studio.
</p>
<hr />

<img height="300" src="https://github.com/ggmartins/ggmartins/assets/2147779/5934d139-a39f-4c83-8045-a9615723b430">

<p align="center">
  Figure 5. BEADChallenge.org analytics, where the internet speeds are lower (unserved/underserved) in IL, USA? / Satellite Internet Performance: The key technology responsible for bringing Internet to unserved. (Download / Upload in Mbps).
</p>
<hr />

<img width="1304" alt="portifolio_analytics1" src="https://github.com/ggmartins/ggmartins/assets/2147779/7e4c2035-8a0b-4ec9-8437-c89227fff129">
<p align="center">
  Figure 6. Data analysis work for the Internet Equity Initiative group. Does the low-income population have worse internet performance than the high-income? What does it mean to be an underserved or unserved area regarding broadband infrastructure? Is the broadband evolving in the US (2019 - 2021 comparison)?
</p>
<hr />

<p align="center">
  <a href="https://www.youtube.com/watch?v=ix5GTHW4D3U"><img width="720" height="460" src="https://img.youtube.com/vi/ix5GTHW4D3U/0.jpg"></a><br>
  Video 1. First prototype of Netrics Passive in action (aka NetMicroscope). Software implemented in C with libwebsockets, libpcap, html, javascript, jquery, chartjs.<br>[WSJ Study](https://www.wsj.com/graphics/faster-internet-not-worth-it/)
</p>

![image](https://github.com/ggmartins/ggmartins/assets/2147779/099f663f-fc2b-4966-9665-47feed869d8b)

<hr />

|            |            |
|------------|------------|
| [![Alt Text](https://raw.githubusercontent.com/ggmartins/ggmartins.github.io/main/wsj0.jpeg)](https://raw.githubusercontent.com/ggmartins/ggmartins.github.io/main/wsj0.jpeg) | [![Alt Text](https://raw.githubusercontent.com/ggmartins/ggmartins.github.io/main/wsj1.jpeg)](https://raw.githubusercontent.com/ggmartins/ggmartins.github.io/main/wsj1.jpeg) |

![image](https://github.com/ggmartins/ggmartins/assets/2147779/70d63771-0383-45b7-a8da-927d42e4c779)
<p align="center">
    Figure 7. Netrics Passive Schematics developed circa 2015. A $200 kit (Jetson Nano 472 GFLOPS) for high-performance passive packet capture, network monitoring and ML inference. (Image generated with [<a href="https://jdan.github.io/isomer/playground/">IsomerJS</a>]. Full source code [<a href="https://github.com/internet-equity/nm-exp-active-netrics/blob/main/docs/images/isomer/mirror/mirror1.js">here</a>].)
</p>

<hr />

<img width="834" alt="image" src="https://github.com/ggmartins/ggmartins/assets/2147779/24fe1c12-0758-4c5b-8921-7a086f522343">
<p align="center">
      Figure 8. My earlier work (circa 2009-2011) on Deep Packet Inspection (DPI) for Alcatel-Lucent, programming CloudShield/IBM equipment (PacketC / C ). I was the principal engineer for the protocol/app service detection intelligence of the network traffic control engine called Agya. The solution was deployed in the Latin America region, mainly in Brazil. 
</p>

#### A few of my certificates:
<table>
<tr>
<td><img width="798" alt="image" src="https://github.com/ggmartins/ggmartins/assets/2147779/3e824c62-d935-4227-97da-6359cde154b5"></td>
<td><img width="800" alt="image" src="https://github.com/ggmartins/ggmartins/assets/2147779/c69713a9-d0b2-4af1-bf81-8bfe66ebb832"></td>
<td><img width="792" alt="image" src="https://github.com/ggmartins/ggmartins/assets/2147779/76b65502-14cc-41ea-acb2-615731fd4bc5"></td>
</tr>
<tr>
<td><img width="783" alt="image" src="https://github.com/ggmartins/ggmartins/assets/2147779/e297cab0-cab6-4661-b9a6-2c5f67b66615"></td>
<td><img width="798" alt="image" src="https://github.com/ggmartins/ggmartins/assets/2147779/b9efa968-1ae0-4165-862e-9f4a6be685b7"></td>
<td><img width="798" alt="image" src="https://github.com/ggmartins/ggmartins/assets/2147779/4ee22e94-aec7-4e5e-a088-da95ba7e8851"></td>
</tr>
</table>



