Connect to a BT Smart Hub 2 Web interface and fetch some status information.

To use:

    ./bt_smarthub debug

Downloads data from the device, adds field titles where known and dumps all
the information.

## Some useful URLs

None of these URLs need authentication when accessed from the LAN.  Most of
the information is duplicated in more than one place.

The wan_conn.xml endpoint is the most complete data source and thus is the
one downloaded by the script in this repository

- http://192.168.1.254/nonAuth/wan_conn.xml
- http://192.168.1.254/cgi/cgi_basicStatus.js
- http://192.168.1.254/cgi/cgi_home.js
- http://192.168.1.254/cgi/cgi_owl.js
- http://192.168.1.254/cgi/cgi_broadband.js
- http://192.168.1.254/cgi/cgi_helpdesk.js

