# libbig_int

[![Build Status](https://travis-ci.org/mlafeldt/libbig_int.svg?branch=master)](https://travis-ci.org/mlafeldt/libbig_int)

libbig_int is a portable C library to calculate integers and bitsets of
arbitrary length. The sources were taken from the [big_int] PHP library by
Alexander Valyalkin.

## Installation

To build and install libbig_int, simply run:

```bash
mkdir build
cd build/
cmake ..
make
make install
```

## Usage

Examples using libbig_int:

- [RSA encryption/decryption](https://github.com/mlafeldt/cb2util/blob/v1.6/cb2_crypto.c#L290-L334)
- [RSA signature validation](https://github.com/mlafeldt/cb2util/blob/v1.6/cb2_crypto.c#L775-L816)

[big_int]: https://github.com/valyala/big_int
