# The Avalon Project

## What

Avalon is a private and secure offsite backup solution for storing sensitive information with self-made infrastructure;
all data is store in sites that communicate internally via meshed peer-to-peer radio connections, stitched together by i2p bridges.

## How

An Avalon network is comprised of two types of nodes: bridge nodes, which have radio and i2p interfaces to provide external connectivity to sites for control plane communication,
and data nodes, whcih are used for storage and can only communicate internally with a radio interface.
The networking stack is provided by [reticulum](https://reticulum.network) due to its mesh networking capabilities accross radio and i2p interfaces.
Currently, IPFS is the distributed filesystem solution, but this is up to change.

## Why

Becuase I want a secure offsite backup solution, and overengineering runs in the family.

## Notes

I will get onto this eventually, but, for now, this repository is a reminder of my plans for this project.
