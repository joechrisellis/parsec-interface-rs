<!--
  -- Copyright 2019 Contributors to the Parsec project.
  -- SPDX-License-Identifier: Apache-2.0
--->
# Parsec Rust Interface

<p align="center">
  <a href="https://crates.io/crates/parsec-interface"><img alt="Crates.io" src="https://img.shields.io/crates/v/parsec-interface"></a>
  <a href="https://docs.rs/parsec-interface"><img src="https://docs.rs/parsec-interface/badge.svg" alt="Code documentation"/></a>
  <a href="https://github.com/parallaxsecond/parsec-interface-rs/actions?query=workflow%3A%22Continuous+Integration%22"><img src="https://github.com/parallaxsecond/parsec-interface-rs/workflows/Continuous%20Integration/badge.svg" alt="CI tests"/></a>
  <a href="https://travis-ci.com/parallaxsecond/parsec-interface-rs"><img src="https://travis-ci.com/parallaxsecond/parsec-interface-rs.svg?branch=master" alt="Travis CI tests"/></a>
</p>

This repository contains an interface library to be used both by the Parsec service and a Rust Client library.
The library contains methods to communicate using the [wire protocol](https://github.com/parallaxsecond/parsec/blob/master/docs/wire_protocol.md).

## Build

The Parsec operations repository is included as a submodule. Make sure to update it first before
trying to compile otherwise it will not work ("`No such file or directory`").

```bash
$ git submodule update --init
```

## License

The software is provided under Apache-2.0. Contributions to this project are accepted under the same license.

This project uses the following third party crates:
* serde (Apache-2.0)
* bincode (MIT)
* num-traits (MIT and Apache-2.0)
* num-derive (MIT and Apache-2.0)
* prost-build (Apache-2.0)
* prost (Apache-2.0)
* bytes (MIT)
* num (MIT and Apache-2.0)
* uuid (Apache-2.0)
* log (MIT and Apache-2.0)
* arbitrary (MIT and Apache-2.0)
* zeroize (MIT and Apache-2.0)
* secrecy (MIT and Apache-2.0)
* derivative (MIT and Apache-2.0)

## Contributing

Please check the [**Contribution Guidelines**](https://parallaxsecond.github.io/parsec-book/contributing.html)
to know more about the contribution process.

