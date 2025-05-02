<div style="background-color:#000000; color:#00ff00; font-family:monospace; padding:20px; border-radius:10px; white-space:pre-wrap; line-height:1.5;">

<span style="color:#ffffff;">sqlmap -u "https://target.site/item.php?id=1" --dbs</span><br>
<span style="color:#6666ff;">[*] starting @ 15:32:18 /2025-05-02/</span><br>
<span style="color:#6666ff;">[*] testing connection to the target URL...</span><br>
<span style="color:#6666ff;">[*] checking if the target is protected by some kind of WAF/IPS...</span><br>
<span style="color:#6666ff;">[*] testing if the parameter 'id' is dynamic...</span><br>
<span style="color:#6666ff;">[*] confirming that the 'id' parameter is injectable...</span><br>
<span style="color:#00ff00;">[+] the back-end DBMS is Oracle</span><br>
<span style="color:#00ff00;">[+] available databases [1]:</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffff00;">[1] brain_core_M4NU</span><br>
<span style="color:#6666ff;">[*] fetching tables from 'brain_core_M4NU'...</span><br>
<span style="color:#6666ff;">[*] extracting table: 'about_me'</span><br>
<span style="color:#00ff00;">[+] retrieved: {</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffffff;">"role": </span><span style="color:#39ff14;">"💻 Red Team Operator at BeeHackers"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffffff;">"learning": </span><span style="color:#39ff14;">"🌱 Continuous training in cybersecurity and ethical hacking"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffffff;">"dev": </span><span style="color:#39ff14;">"🛠️ Developer of offensive security tools"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffffff;">"focus": </span><span style="color:#39ff14;">"💬 CVE and zero-day hunter"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffffff;">"certs": </span><span style="color:#39ff14;">"📜 eJPTv2, eCPPTv3, KLCP"</span><br>
<span style="color:#00ff00;">}</span><br>
<span style="color:#6666ff;">[*] fetched data logged to text files under: '/home/manuel/.sqlmap/output/target.site'</span><br>

</div>
