Trail
-----
Sick and tired of being tracked by all the websites you visit. Trail will help you to block tracking pixels for various websites and vendors.

Usage
-----
To enable trail just run `./trail --enable` and it will add a block of known hosts to your hosts file. To disable it again just run `./trail --disable`.

Sniffing
--------
If you want to find new hosts to block you can start a sniffer with `./trail --sniff` and start do some browsing on the web. The sniffer script will automatically try to detect hosts that seem to be tracking your behavior. All these hosts are logged to the `hosts.sniff` file. 

Keep in mind that the sniffer doesn't work for https connections.

Todo
----
* For the moment the regex used to detect a tracking pixel is very simple, this can be hugely improved

Tested on
---------
For the moment this is only tested on Mac OSX Yosemite.