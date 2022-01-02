# NS3 TCP Version Comparison
## Execute
* Move tcp-comparison.cc  to scratch folder in NS3 
* Run `sudo ./waf --run scratch/tcp-comparison --command-template="%s --transport_prot={TcpVersion}"` to execute
  * `sudo ./waf --run scratch/tcp-comparison --command-template="%s --transport_prot=TcpNewReno --duration=10 --bandwidth=20Mbps --access_bandwidth=20Mbps"`
