# edi-raspbian

edi configuration for Raspbian cross compilation and emulated Raspbian.

To generate a Debian buster/Raspbian multiarch cross compilation container use the following command:

``` bash
sudo edi -v lxc configure raspbian-buster-cross buster-cross.yml
```

Use the following command to generate an _emulated_ Raspbian lxc container:

``` bash
sudo edi -v lxc configure raspbian-buster-emulated buster-emulated.yml
```

Please note that no services get started in the _emulated_ container and thus
no ssh access will be possible. Due to the emulation the program execution is slow.

To enable networking within the emulated container use the following command
to bring up the default network interface:

``` bash
sudo ip link set eth0 up && sudo dhclient eth0
```

For more information please read the [edi documentation](https://docs.get-edi.io) and 
[this blog post](https://www.get-edi.io/Cross-Compiling-for-Raspbian/).
