<center>
    <h1 align="center">AdBlock List</h1>
    <h4 align="center">A multi-purpose adblocker and skip-bypass for the <strong>Windows, Mac and Linux</strong></h4>
    <h5 align="center">Works with PiHole and Adguard</h5>
</center>

Usage
-----

### Windows
Replace hosts file in your windows system
```
c:\Windows\System32\Drivers\etc\hosts
```

To access the hosts file using the file explorer you simply need to log in to an administrator account and enter `%SystemRoot%\System32\drivers\etc\` into the address bar. If it is not there, it may be hidden.

Or

Open the Run App
Press the Windows Key + R to open the Run app
In the Open: text field, type in this string of text:
```
%SystemRoot%\System32\drivers\etc\hosts
```
### MacOS & linux
Open Terminal and type this command below
```
sudo nano /etc/hosts
```
Then copy & paste content of hosts file to this file.

The other way is just download hosts file from [Phishing](https://github.com/x-o-r-r-o/AdBlock-List/raw/main/Phishing/hosts) and replace in /etc/ folder on mac.

What is a hosts file?
-------------------

A hosts file maps hostnames (i.e. domains) to IPs. It does the same job as a DNS, but the lookup is made entirely locally.

This feature is used to map all the domains to blacklist to the [`0.0.0.0` IP meta-address](http://en.wikipedia.org/wiki/0.0.0.0).

What does hosts file do?
-------------------

Editing the hosts file in Windows lets you change the IP address that a given website resolves to on your computer. This allows you to override the destination that a website’s DNS zone file would normally take you to.

Why i must change or replace hosts file with yours?
-------------------

Ads, shock sites, hijack sites, malware servers, click trackers, popup traps (sites that make you confirm on and on), spam sending servers.

How it works?
-------------------

Normally when you enter a URL (such as Facebook.com) into the address bar of your web browser it will send a Domain Name System (DNS) request to a server. DNS changes the names of these human-readable domains into an IP address such as 123.123.123.123 (for IPv4) or 7d6f:90de:8aa4:1057:161f:9ffe:bf3c:87eb (for IPv6) that identifies the server’s location.

Is it enough?
-------------

Using such a hosts file ensures adblocking, and a good level of privacy from tracker networks. However, I recommend to complement it with a browser plugin that can block trackers on a site-by-site basis. [Privacy Badger](https://www.eff.org/privacybadger) or [Ghostery](https://www.ghostery.com/try-us/download-browser-extension/) are good choices.

> Analytics software that tracks your behaviour can be served by each site from its own domain, thus being impossible to block on a DNS level.
> Moreover, some trackers (most notably, Google Analytics) are so common that some websites break when they are blocked, and they are thus not blocked by the hosts file. In order to prevent them from loading, yet easily load them if a site seems broken, an interactive browser plugin is easier.

License
-------

MIT
