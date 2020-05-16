# Awesome Space

## List of resources for Aerospace and Rust

### Feel free to open PR to add additional links and resources.

## Table of contents

##### General info
- [Organisations](#organisations)
  - [Consultative Committee for Space Data Systems](#consultative-committee-for-space-data-systems-ccsds)
- [Agencies (Comprehensive list of active agencies)](#agencies)
  - [CNES (French)](#cnes)
  - [ESA (Europe)](#esa)
  - [ISRO (India)](#isro)
  - [JAXA (Japan)](#jaxa)
  - [NASA (US)](#nasa)

##### AeroRust
- [Companies](#companies)
- [Videos](#videos)
- [Orbital Index](#orbital-index)
- [Build your own...](#build-your-own)
  - [Rover (JPL)](#rover)
- [Crates](#crates)
  - [Labrador-LDPC - encoding and decoding low-density parity check (LDPC) error correcting codes](#labrador-ldpc)
  - [CCSDS Primary Header - CCSDS Primary Header impl of the Space Packet Protocol standard](#ccsds-primary-header)
  - [NYX - astrodynamical toolkit library](#nyx)
  - [YANP - Yet Another NMEA Parser](#yanp)
  - [BP7 - Bundle Protocol 7 encoding/decoding library](#bp7)
  - [DTN7 - Delay-tolerant Networking Daemon and CLI tools](#dtn7)

## Organisations

### Consultative Committee for Space Data Systems (CCSDS)

  > Founded in 1982 by the major space agencies of the world,
  > the CCSDS is a multi-national forum for the development of communications and data systems standards for spaceflight.

  Source: https://ccsds.org


  - Website: https://ccsds.org

## Agencies

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

## Companies

#### Kubos
- Website: https://www.kubos.com/
- Github: https://github.com/kubos

#### Exodus Orbitals
- Website: https://exodusorbitals.com

## Videos

- [Lightning Talks: Rust In Space — myrrlyn](https://www.youtube.com/watch?v=xYDKcoS26ZM)
- [RustConf 2018 - Space, The Rusty Frontier by Ryan Plauche](https://www.youtube.com/watch?v=y5Yd3FC-kh8)
- [2018 Corroding Space (Flight Software Workshop)](https://www.youtube.com/watch?v=2pA1xMI5EJs)
- [2018 Rust for FSW (Flight Software Workshop)](https://www.youtube.com/watch?v=ET1QdkAK-_U)

## Orbital Index

- Website: https://orbitalindex.com
- [awesome-space list](https://github.com/orbitalindex/awesome-space)

## Build your own...

#### Rover
  JPL's (Jet Propulsion Laboratory) Open Source Build-It-Yourself Rover

  - Website: https://opensourcerover.jpl.nasa.gov/

## Crates


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
  
  A Work-In-Progress [impelementation](https://github.com/dtn7/dtn7-rs) of the upcoming delay-tolerant networking [standard](https://tools.ietf.org/html/draft-ietf-dtn-bpbis-24). 
  This crate uses *BP7* to provide a dtn daemon (with routing, convergence layers, etc) and command line tools.

  crates.io: https://crates.io/crates/dtn7

  Type: **?**
