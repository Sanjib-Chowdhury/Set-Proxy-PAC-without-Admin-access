# Set-Proxy-PAC-without-Admin-access
Organisations usually block proxy setting option through group policy. Also, users usually don't have Admin access to change the proxy setting. This script helps security engineers to set a different proxy for testing. This change is temporary &amp; is overridden by the group policy.

Sample output below -

***************************

31 December 2021 09:18:02


***************************

ProxyEnable AutoConfigURL ProxyServer          
----------- ------------- -----------          
          1               http://actualpacserver/actualproxypac.pac



ProxyEnable AutoConfigURL                              ProxyServer           
----------- -------------                              -----------           
          1 http://changedpacserver/changedproxypac.pac 192.168.0.1:8080


**********************************************************
Report bug to sanjib_25@yahoo.com
Visit https://github.com/Sanjib-Chowdhury for more tools.

