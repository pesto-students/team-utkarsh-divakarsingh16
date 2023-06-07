What is a protocol stack, and how is it used in web development?
Ans: A protocol stack is set of network protocal layers that work together. A protocol stack is a prescribed heirarchy of software layers, starting from the application layer at the top to link layer at the bottom.

Link-layer :
Starting from  link layer it is the most basic or lowest level classifiation of communction protocol. It deals with sending information on the same local network and transilating data from higher layer to physical layer.
protocol in the link layer describes how data interacts with the transmission medium,such as electronic signals sent over specific hardware.Unlike other layers link layer protocol are dependent on the hardware being used.

Network-layer or Internent layer:

Protocols in the network layer describe how data is sent and recived over the internet. The process involves packing data into packets, adressing and transmitting the packets and receiving incoming data. IP is a connectionless protocol, meaning that it provides no guarantee that packets are sent or recieved in the rigth order along the same path or even in their entirety.

Reliability is handled by other protocols in the suite, such as in the transport layer. There are currently two versions of Ip in use: IPV4, and IPV6.Both versions describe how devices on the Internet are assigned IP adresses . 

IPV4 is more widely used,but has only 32bits for addressing,allowing for about 4.3billion possible addresses. These are running out, and IPV4 will eventually suffer from address. These are running out, and IPV4 will eventually suffer from address exhasution as more 
and more people use more devices on the Internet. The successor version IPV6 aims to solve address exhaustion by using 128bits for addresses. This provides, um, a lot more addresses possibilites.

Transport layer Protocols:

The transport layer presently encapuslates TCP and UDP . Like IP, UDP is connetcion less and can be used to prioritize time over realability.

Tcp on other hand , is a connection-oriented transport layer protocal that priotize relaibilty over latency , or time. TCP describes transferring data  in the same order as it was sent, retransmitting lost packets, and controls affecting the rate of data transmission.

Application layer protocal:

The application  layer describes the protocols that software application intaracts most often. The specification includes descriptions of the remote login protocol Telnet, the FTP(file tranfer protocol) and the SMTP(Simple mail transfer protocol).
Also included in the application layer are the Hypertext Transfer Protocol (HTTP) and its successor, Hypertext Transfer Protocol Secure (HTTPS).


2) What are the different types of web servers, and how do they differ in terms of functionality and performance ?
ANS : Every Website sits on a computer known as a Web server. This server is always connected to the internet. Every Web server that is connected to the Internet is given a unique address made up of a series of four numbers between 0 and 255 separated by periods. For example, 68.178.157.132 or 68.122.35.127.

Examples of different web servers are Apache, microsoft IIS, NGINX , Apache Tomcat, lightTpd.

3)What is web hosting, and what are the different types of hosting services available for websites?

ANS: A web hosting service is a type of Internet hosting service that hosts websites for clients, i.e. it offers the facilities required for them to create and maintain a site and makes it accessible on the World Wide Web. 
Different types of web hosting services are shared Hosting , cloud Hoting ,Managed Hosting, VPS Hosting , Deidcated Hosting.

4)What is scaling, and why is it important for web applications? How does scaling differ for vertical and horizontal scaling?

ANS: The scalability of an application can be measured by the number of requests it can effectively support simultaneously. The point at which an application can no longer handle additional requests effectively is the limit of its scalability. This limit is reached when a critical hardware resource runs out, requiring different or more machines. Scaling these resources can include any combination of adjustments to CPU and physical memory (different or more machines), hard disk (bigger hard drives, less “live” data, solid state drives), and/or the network bandwidth (multiple network interface controllers, bigger NICs, fiber, etc.).

Scaling horizontally and scaling vertically are similar in that they both involve adding computing resources to your infrastructure. There are distinct differences between the two in terms of implementation and performance.

Horizontal scaling means scaling by adding more machines to your pool of resources (also described as “scaling out”), whereas vertical scaling refers to scaling by adding more power (e.g. CPU, RAM) to an existing machine (also described as “scaling up”).

One of the fundamental differences between the two is that horizontal scaling requires breaking a sequential piece of logic into smaller pieces so that they can be executed in parallel across multiple machines. In many respects, vertical scaling is easier because the logic really doesn’t need to change. Rather, you’re just running the same code on higher-spec machines. However, there are many other factors to consider when determining the appropriate approach.

5)What is SEO (Search Engine Optimization), and how can web developers optimize their websites for better search engine rankings?
ANS: Search engine optimization is the science of improving a website to increase its visibility when people search for products or services. The more visibility a website has on search engines, the more likely it is that brand captures business. 

SEO optimization can done by using symatical friendly tags in website, back links and Accurately summarize the page content,Use Data Highlighter and Markup Helper.