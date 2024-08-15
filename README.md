<h1>Splunk Investigation 2</h1>

<h2>Description</h2>
Our organization's website experienced high resource usage. The traffic pattern suggested a port or vulnerability scan rather than a DDoS attack, as requests came from a single IP. Using a Splunk query (sourcetype="fortigate_utm", hostname="OurWebSite.com", "vulnerability"), I identified 4,144 events targeting our webserver (dstip) with XXX.Web.Vulnerability.Scanner (attack) from one IP address (srcip). FortiGate UTM's log enrichment revealed the source IP was from the United States (srccountry).
<br />

<h2>Lab Certification:</h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/WadkbRD.png" height="80%" width="80%" alt="portfolio"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
