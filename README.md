# NetworkApplications.py
Network Applications

A collection of Network Applications
positional arguments:
  {ping,p,traceroute,t,mtroute,mt,web,w, proxy,x}
                      sub-command help 
ping (p)                      run ping
traceroute (t)          run traceroute
mtroute (mt)            run traceroute
web (w)                 run web server
proxy (x)               run proxy
options:
-h, --help
show help message and exit

e.g. python3 NetworkApplications.py traceroute -p icmp google.com
NOTE: Only works on computers with SUDO privileges
