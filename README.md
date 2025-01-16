# lewhfree/CoreCrypto

Fix of corecrypto compilable on armv6hf - used for lewhfree/altserver-linux

OG description - Rewrite of Apple CoreCrypto for the Darling project.

## Building
We use Python 3 with the [`cryptography`](https://pypi.org/project/cryptography/) module to generate some of our test data, so make sure you have those installed before building.

```
$ git clone https://github.com/lewhfree/corecrypto
$ cd corecrypto
$ mkdir build
$ cd build
$ cmake ..
$ make
$ sudo cp libcorecrypto.so /usr/lib 
```
