Support for CentOS 7

The one click Startup node is connected to the tenon VPN network of SAMA network, providing server nodes and bandwidth mining to obtain revenue.

Daily revenue of mining = total advertising revenue * (bandwidth consumed by nodes / bandwidth consumed by the whole platform) * (1 - platform revenue coefficient)
PS: the profit coefficient of the platform is currently 5%, and the network is adjusted dynamically

Access steps of VPS or VDS

Step 1 download code
yum install -y wget &amp;&amp; wget  https://github.com/tenondvpn/tenonvpn-join/archive/5.0.2.zip

Step 2 initializes the environment, restarts the system after execution, and the program starts automatically
yum install -y unzip &amp;&amp; unzip 5.0.2.zip &amp;&amp; mv tenonvpn-join-5.0.2 tnet &amp;&amp; cd tnet &amp;&amp; sh init_ env.sh
Wait for the installation to complete and restart the machine

Step 3 get mining private key and query website
sh get_ private_ key.sh
sh get_ mining_ url.sh
Open the website, you can query the daily income of this node, and transfer money.

    
    


