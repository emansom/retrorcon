# RetroRCON
An gRPC service definition to standardize RCON communication for Habbo emulation once and for all

For long, different emulators and CMSes have been implementing their own RCON protocol, making CMS migration tedious. This project aims to change that by standardizing the RCON protocol, using the industry-standard gRPC made and used by Google.

## Client implementations

To integrate housekeeping functionality, player refresh, infobus polls and more into your CMS

- PHP
- Go
- ASP.NET
- Ruby
- node.js

## Server implementations

Server implementations are to be used within emulators

- Java
- C#.NET

## Requirements
- gRPC PHP extension
- Protobuf PHP extension
- composer

## A feature is missing!
Please create an issue/bug report in this repository and we'll work on implementing it.

## How to contribute
See CONTRIBUTING.md
