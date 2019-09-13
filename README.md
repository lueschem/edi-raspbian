# edi-raspbian

edi configuration for emulated raspbian and raspbian cross compilation.

Use the following command to generate a Raspbian lxc container:

``` bash
sudo edi -v lxc configure raspbian-buster-emulated buster-emulated.yml
```

To generate a Debian buster/Raspbian multiarch cross compilation container use the following command:

``` bash
sudo edi -v lxc configure raspbian-buster-cross buster-cross.yml
```

For more information please read the [edi documentation](https://docs.get-edi.io) and 
[this blog post](https://www.get-edi.io/Cross-Compiling-for-Raspbian/).
