<div align="center">

## Convert IP into hostname


</div>

### Description

How do I convert a numeric IP address like 199.1.32.90 into a hostname like star.blackstar.com?

Unfortunately due to an unintended side effect (i.e. a bug) in Java's caching of IP addresses and hostnames, Java 1.0 can't convert numeric IP addresses into hostnames. However this is straightforward in Java 1.1. For example,

(Java FAQ:found on the web at:http://sunsite.unc.edu/javafaq/javafaq.html)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[N/A](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/empty.md)
**Level**          |Unknown
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.1\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/convert-ip-into-hostname__2-259/archive/master.zip)





### Source Code

String hostname = InetAddress.getByName("199.1.32.90").getHostName()

