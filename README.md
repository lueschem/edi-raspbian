# edi-raspbian

edi configuration for emulated raspbian and raspbian cross compilation.

Use the following command to generate a Raspbian lxc container:

``` bash
sudo edi -v lxc configure raspbian-stretch-emulated stretch-emulated.yml
```

To generate a Debian stretch/Raspbian multiarch cross compilation container use the following command:

``` bash
sudo edi -v lxc configure raspbian-stretch-cross stretch-cross.yml
```

For more information please read the [edi documentation](https://docs.get-edi.io) and 
[this blog post](https://www.get-edi.io/Cross-Compiling-for-Raspbian/).
