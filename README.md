# knx_rs

[![BSD licensed](https://img.shields.io/badge/license-BSD-blue.svg)](LICENSE)
[![Build Status](https://travis-ci.org/uwearzt/knx_rs.svg?branch=master)](https://travis-ci.org/uwearzt/knx_rs)
[![crates.io](https://meritbadge.herokuapp.com/knx_rs)](https://crates.io/crates/knx_rs)
[![Gitter](https://badges.gitter.im/knx_rs/Lobby.svg)](https://gitter.im/knx_rs/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The `knx_rs` crate implements a
[KNX](https://en.wikipedia.org/wiki/KNX_(standard)) Library able to communicate over IP (Multicast) and Serial.

It is used to create some user specific Actors and Sensors on the twisted
wire bus (TP1).

## Hardware

[TP-UART 2 Evaluation Board](http://www.opternus.com/uploads/media/PCBA_UP117-12_datasheet_v5_2012-05-30.pdf)
[TPUART2](http://www.opternus.com/uploads/media/TPUART2_Datenblatt_20130806.pdf)

## Platforms

For developing purposes i use macOS, and at the moment it is tested on macOS only. Tests for a Cortex M4 controller will be added soon.

## Usage

Add `knx_rs` as a dependency in `Cargo.toml`:

```toml
[dependencies]
knx_rs = "0.0.1"
```

### Cross compiling

## Contributors

* mail@uwe-arzt.de Uwe Arzt

## License

see the LICENSE file.
