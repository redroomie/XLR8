![bhj(1)](https://github.com/redroomie/TorghostNG/assets/142141092/642ecf46-08b1-4fbe-a583-4c167eb1f82b)




# About XLR8
XLR8 fastest way to connect and stay anonymous without any proxy & socks5 in tor 
XLR8 is a tool that make all your internet traffic anonymized through Tor network.

# Before you use XLR8 ( Tor Browser is recommended )
* For the goodness of Tor network, BitTorrent traffic will be blocked by iptables. Although you can bypass it with some tweaks with your torrent client 😥. It's difficult to completely block all torrent traffic.
* For security reason, TorghostNG is gonna disable IPv6 to prevent IPv6 leaks (it happened to me lmao).

# Installing XLR8
TorghostNG currently supports:
* GNU/Linux distros that based on Arch Linux
* GNU/Linux distros that based on Debian/Ubuntu
* GNU/Linux distros that based on Fedora, CentOS, RHEL, openSUSE
* [Solus OS](https://getsol.us)
* [Void Linux](https://voidlinux.org)
* Anh the elder guy: [Slackware](http://slackware.com)
* (Too much package managers for one day :v)

To install TorghostNG, open your Terminal and enter these commands    
    
    git clone https://github.com/redroomie/XLR8
    cd XLR8
    sudo python3 XLR8 -s -m wlan0  /  eth0 
    
you can use `sudo python3 XLR8.py` to run XLR8.
use `sudo python3 torghostng.py -x` to stop XLR8

# Help
    OPTIONS:
      -h, --help      Show this help message and exit
      -s, --start     Start connecting to Tor
      -x, --stop      Stop connecting to Tor
      -r, --renew     Renew the current Tor circuit
      -id COUNTRY ID  Connect to Tor exit node of a specific country. Go to CountryCode.org to search country ID
      -mac INTERFACE  Randomly change MAC address. Use 'ifconfig' to show interface devices
      -c, --checkip   Check your current IPv4 address
      --dns           Use this to fix DNS when website address can't be resolved
      -l, --language  Change the display language. English is the default
      --list          Show the available languages list
      -u, --update    Check for update
      --nodelay       Disable delay time

You can combine multiple choices at the same time, such as:
* `sudo python3 XLR8 -s -m`: to connect & Changing MAC address before connecting
* `sudo python3 XLR8 -c -m` : Checking IP address and changing MAC address
* `sudo python3 XLR8 -x`: to stop :)
* ...
* ...

It's recommended that you should use [NoScript](https://noscript.net) before before surfing the web with Tor. NoScript shall block JavaScript/Java/Flash scripts on websites to make sure they won't reveal your real identify.

# And please
* **Don't spam or perform DoS attacks with Tor.** It's not effective, you will only make Tor get hated and waste Tor's money.
* **Don't torrent over Tor.** If you want to keep anonymous while torrenting, use a no-logs VPN please.


Version 1.1
* Check your IPv6
* Change all "TOR" to "Tor"
* Block BitTorrent traffic
* Auto disable IPv6 before connecting to Tor



# And finally
You can help me by telling me if you find any bugs or issues. Thank you for using my tool 😊
