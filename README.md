# edi-raspbian

edi configuration for emulated raspbian and raspbian cross compilation.

Use the following command to generate a Raspbian lxc container:

``` bash
sudo edi -v lxc configure raspbian-jessie-emulated jessie-emulated.yml
```

To generate a Debian jessie/Raspbian multiarch cross compilation container use the following command:

``` bash
sudo edi -v lxc configure raspbian-jessie-cross jessie-cross.yml
```

For more information please read the [edi documentation](http://docs.get-edi.io) and 
[this blog post](http://www.get-edi.io/Cross-Compiling-for-Raspbian/).
