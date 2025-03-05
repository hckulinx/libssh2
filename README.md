# libssh2 - SSH2 library

1. According to the requirements of the "GM-T0129-2023 Secure shell cryptography Protocol Specification" 
and the support of the national encryption algorithm in openssl, 
implement LIBSSH2's support for the national encryption algorithm suite, 
including the national encryption algorithms SM2/SM3/SM4, as well as the national encryption SSH negotiation protocol.

2. National testing requirements such as security evaluation require remote channel management to support national encryption.
 
3. Add national encryption support to libssh2 to comply with national testing standards.


libssh2 is a library implementing the SSH2 protocol, available under
the revised BSD license.

[Web site](https://libssh2.org/)

[Mailing list](https://lists.haxx.se/listinfo/libssh2-devel)

[BSD Licensed](https://libssh2.org/license.html)

[Web site source code](https://github.com/libssh2/www)

Installation instructions:
 - [for CMake](docs/INSTALL_CMAKE.md)
 - [for autotools](docs/INSTALL_AUTOTOOLS)
