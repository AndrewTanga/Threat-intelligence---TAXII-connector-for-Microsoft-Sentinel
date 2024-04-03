# Threat-intelligence---TAXII-connector-for-Microsoft-Sentinel

<b>First thing that we have to do is to install 'Threat Intelligence' for Sentinel in 'Content Hub'<b>
![Screen Shot 2024-04-02 at 8 30 44 PM](https://github.com/AndrewTanga/Threat-intelligence---TAXII-connector-for-Microsoft-Sentinel/assets/93886645/b5bbaff1-fd96-4b1b-945e-6b402cbb7604)

<b>Manage 'Threat Intelligence' and go to 'Open connector page' (I already loaded the feed form so I got some logs in the chart)<b>
![Screen Shot 2024-04-02 at 8 34 59 PM](https://github.com/AndrewTanga/Threat-intelligence---TAXII-connector-for-Microsoft-Sentinel/assets/93886645/0187327e-ef21-42e1-8cc8-2134d60df2f1)

<b>After creating account on Pulsedive I configure TAXII server and connected to Microsoft Sentinel, then ingested 'test collection'<b>
<b>Now Microsoft Sentinel has table 'ThreatIntelligenceIndicator' with enormous pack of events<b>
![Screen Shot 2024-04-02 at 8 51 38 PM](https://github.com/AndrewTanga/Threat-intelligence---TAXII-connector-for-Microsoft-Sentinel/assets/93886645/a946d85b-658e-4e64-9057-521a8fd0b837)

<b>Analyzing one of the records, we can see 'ThreatType' - malicious-activity, 'DomainName' - su, statistically it is can be dangerous domain becouse is less tightly regulated than other top-level domain names<b>
![Screen Shot 2024-04-02 at 8 55 40 PM](https://github.com/AndrewTanga/Threat-intelligence---TAXII-connector-for-Microsoft-Sentinel/assets/93886645/60f27a4a-8bac-439a-ba78-c8844ecbf4a3)
