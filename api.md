## Device query ##

`/api/s/`_site_`/stat/device/`

Returned JSON, focusing on identifying switches:

    data:
        list of devices
            ip: device IP address
            name: device name
            type: usw (uap ugw)
            port_table: list of ports
                port_idx: port number
                name: port description

`/api/s/`_site_`/get/setting/`

Returned JSON:

    data:
        list of setting types
            key: setting type
            key='mgmt':
                x_ssh_username: username for ssh to device
		x_ssh_password: password for ssh to device
