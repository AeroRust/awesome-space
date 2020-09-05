# Awesome Space

#### List of resources for Aerospace  and Rust

Feel free to open PR to add additional links and resources (including your own crates and project! 🥳 ).

#### Table of contents

##### [AeroRust resources](#aerorust-resources-1)
- [Companies](#companies)
- [Videos](#videos)
- [Crates](#crates)

  AeroRust crates:

  - [NMEA - NMEA 0183 sentence parser (AeroRust)](#nmea)
  - [arsdk-rs - Parrot drones SDK (AeroRust)](#arsdk-rs)
  - [Splice - a DSL for Software-Defined Satellite Applications (AeroRust)](#splice)

  Other crates:
  - [yaiouom - Extensible, strongly-typed units of measure, with a custom type system implemented as a linter](#yaiouom)
  - [Labrador-LDPC - encoding and decoding low-density parity check (LDPC) error correcting codes](#labrador-ldpc)
  - [CCSDS Primary Header - CCSDS Primary Header impl of the Space Packet Protocol standard](#ccsds-primary-header)
  - [NYX - astrodynamical toolkit library](#nyx)
  - [YANP - Yet Another NMEA Parser](#yanp)
  - [BP7 - Bundle Protocol 7 encoding/decoding library](#bp7)
  - [DTN7 - Delay-tolerant Networking Daemon and CLI tools](#dtn7)
- Other resources
  - [Units of Measure in Rust with Refinement Types](#units-of-measure-in-rust-with-refinement-types)
  - [Current State of Embedded Rust for Flight Controllers](#current-state-of-embedded-rust-for-flight-controllers)

##### [Aerospace resources](#aerospace-resources-1)

- [Orbital Index](#orbital-index)
- [Build your own...](#build-your-own)
  - [Rover (JPL)](#rover)
  - [Ground station (NyanSat)](#ground-station)
- [Organisations](#organisations)
  - [Consultative Committee for Space Data Systems](#consultative-committee-for-space-data-systems-ccsds)
- [Agencies (Comprehensive list of active agencies)](#agencies)
  - [CNES (French)](#cnes)
  - [ESA (Europe)](#esa)
  - [ISRO (India)](#isro)
  - [JAXA (Japan)](#jaxa)
  - [NASA (US)](#nasa)

## AeroRust resources

### Companies

#### Kubos
- Website: https://www.kubos.com/
- Github: https://github.com/kubos

#### Exodus Orbitals
- Website: https://exodusorbitals.com

### Videos

List of all AeroRust videos/talks can be found in this playlist: https://www.youtube.com/playlist?list=PLXz6wWXh9PiRWhTMz70ulVwTAWki_ELs4

- [Drone Control - Controlling a drone using Rust over WiFi (`arsdk-rs` crate)](https://www.youtube.com/watch?v=e2mJq9qm_Io)
---
- [Lightning Talks: Rust In Space — myrrlyn](https://www.youtube.com/watch?v=xYDKcoS26ZM)
- [RustConf 2018 - Space, The Rusty Frontier by Ryan Plauche](https://www.youtube.com/watch?v=y5Yd3FC-kh8)
- [2018 Corroding Space (Flight Software Workshop)](https://www.youtube.com/watch?v=2pA1xMI5EJs)
- [2018 Rust for FSW (Flight Software Workshop)](https://www.youtube.com/watch?v=ET1QdkAK-_U)

### Crates

### _AeroRust crates_

#### NMEA

  NMEA 0183 sentence parser for Rust. Currently only GGA, GSV, GSA, VTG and RMC sentences are supported.

  Repository: https://github.com/AeroRust/nmea
  crates.io: https://crates.io/crates/nmea
  Wikipedia: https://en.wikipedia.org/wiki/NMEA_0183

#### arsdk-rs

  SDK for https://parrot.com drones

  Repository: https://github.com/AeroRust/arsdk-rs
  Parrot: https://parrot.com

#### Splice

  Splice is a DSL for Software-Defined Satellite Applications

  Repository: https://github.com/AeroRust/splice

### _Other crates_

#### yaiouom
  Extensible, strongly-typed units of measure, with a custom type system (based on F#'s unit of measures) implemented as a linter.

  This crate implements a mechanism of units of measure. It may be used to manipulate all sorts of measures, including physics/engineering (m, kg, s, A, m * s ^ 1, ...), currencies (EUR, USD, ...), statistics (dollars per barrel, engineers per lightbulb, dollars per household per year, ...)

  crates.io: https://crates.io/crates/yaiouom

  Repository: https://github.com/Yoric/yaiouom


#### Labrador-LDPC
  A crate for encoding and decoding low-density parity check (LDPC) error correcting codes.

  crates.io: https://crates.io/crates/labrador-ldpc

  Type: **no_std only**

#### CCSDS Primary Header
  This crate contains an implementation of the CCSDS standard called Space Packet Protocol,
  which defines a packet header called the CCSDS Primary Header.

  crates.io: https://crates.io/crates/ccsds_primary_header

  Type: **?**

#### NYX
  Nyx is a high fidelity, fast, reliable and validated astrodynamical toolkit library written in Rust.

  The target audience is researchers and astrodynamics engineers.
  The rationale for using Rust is to allow for very fast computations, guaranteed thread safety,
  and portability to all platforms supported by Rust.

  crates.io: https://crates.io/crates/nyx-space

  Repository: https://gitlab.com/chrisrabotin/nyx

  Type: **?**

#### YANP
  YANP - Yet Another NMEA Parser.

  A no_std Rust NMEA 0183 sentence parser.

  crates.io: https://crates.io/crates/yanp

  Type: **parsing + no_std**

#### BP7
  Bundle Protocol 7 encoding/decoding library.

  A portable Work-In-Progress [impelementation](https://github.com/dtn7/bp7-rs) of the upcoming delay-tolerant networking [Bundle Protocol](https://tools.ietf.org/html/draft-ietf-dtn-bpbis-24).
  Support for DTN (Delay-Tolerant Network) as well as IPN (InterPlanetary Network) addressing, custom canonical blocks and restricted environments such as wasm.

  crates.io: https://crates.io/crates/bp7

  Type: **?**

#### DTN7
  Delay-tolerant Networking Daemon and CLI tools.

  A Work-In-Progress [implementation](https://github.com/dtn7/dtn7-rs) of the upcoming delay-tolerant networking [standard](https://tools.ietf.org/html/draft-ietf-dtn-bpbis-24).
  This crate uses *BP7* to provide a dtn daemon (with routing, convergence layers, etc) and command line tools.

  crates.io: https://crates.io/crates/dtn7

  Type: **?**

### Other resources

#### Units of Measure in Rust with Refinement Types

https://yoric.github.io/post/uom.rs/

Also make sure to check out the crate @TODO

#### Current State of Embedded Rust for Flight Controllers

https://gist.github.com/tstellanova/81c963f556522447dd007a0c3a84ebc3

## Aerospace resources

### Orbital Index

- Website: https://orbitalindex.com
- [awesome-space list](https://github.com/orbitalindex/awesome-space)

### Build your own...

#### Rover
  JPL's (Jet Propulsion Laboratory) Open Source Build-It-Yourself Rover

  - Website: https://opensourcerover.jpl.nasa.gov/

#### Ground station
  NyanSat is a guided challenge that walks you through building your own ground station to track satellites, receiving signals, understanding how data is encoded, and looking at images from space.

  - Website: https://nyan-sat.com/

### Organisations

#### Consultative Committee for Space Data Systems (CCSDS)

  > Founded in 1982 by the major space agencies of the world,
  > the CCSDS is a multi-national forum for the development of communications and data systems standards for spaceflight.

  Source: https://ccsds.org

  - Website: https://ccsds.org

### Agencies

  Full list of agencies can be found in [Wikipedia.org](https://en.wikipedia.org/wiki/List_of_government_space_agencies#List_of_space_agencies)

#### CNES
- The Centre national d'études spatiales (France)
- Website: [https://cnes.fr](https://cnes.fr/en)
- Github: https://github.com/cnes

#### ESA
- European Space Agency (Europe)
- Website: https://www.esa.int
- Github: https://github.com/esa
- Respository: https://essr.esa.int

#### ISRO
- Indian Space Research Organisation (India)
- Website: https://www.isro.gov.in

#### JAXA
- Japan Aerospace Exploration Agency (Japan)
- Website: https://global.jaxa.jp
- Github: -

#### NASA
- National Aeronautics and Space Administration (US)
- Website: https://nasa.gov
- Github: https://github.com/nasa
- Open source projects: https://opensource.gsfc.nasa.gov
- Software projects (free and other): https://software.nasa.gov

