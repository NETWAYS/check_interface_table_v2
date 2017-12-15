# check_interface_table_v2

> **Note**
>
> The current active developed versions is [interfacetable_v3t](https://github.com/Tontonitch/interfacetable_v3t).

`check_interface_table_v2.pl` is an Icinga/Nagios plugin that allows you to monitor
one network device (e.g. router, switch, server) without knowing each interface
in detail. Only the hostname (or ip address) and the snmp community string are
required.


### Requirements

* Perl libraries: `Config::General`, `Net::SNMP`


### Usage

    # ./check_interface_table_v2.pl -H server1 -C public
    
More details using

    # ./check_interface_table_v2.pl -h

