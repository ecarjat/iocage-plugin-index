# HOWTO install a plugin

`
% sudo iocage fetch -g https://github.com/ecarjat/iocage-plugin-index.git -P influxdb ip4_addr="<interface_name>|<ipaddr>/<netmasq_cidr>" vnet=off bpf=off
`

Where `<interface_name>` is `ix0` and `<ipaddr>/<netmasq_cidr>` is like `192.168.0.1/24`

VNET is not working at the moment on 11.3-RELEASE
