<h1>Capturing failed login attempts and analyzing them via Event Viewer</h1>

Log out of the VM. <br/>
Log in with incorrect username and password to purposefully fail logon.  <br/>
Do this four times<br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/2.1%20log%20out%20vm%2C%20remote%20log%20in%20as%20testlogin%2C%20fail%204%20times.png)
<br />

Remote into VM <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/2.2%20remote%20into%20vm.png)
<br />

We can view Event Viewer security logs by going to Event Viewer -> Windows Logs -> Security<br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/2.3.1%20event%20viewer%20logs.png)
<br />

Go to Event Viewer and find eventID 4625 indicating failed logon<br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/2.3%20event%20viewer%204625%20audit%20failure.png)
<br />
