# Linux kernel

[![pipeline status](https://gitlab.com/trenchboot1/3mdeb/linux/badges/linux-sl-5.5/pipeline.svg)](https://gitlab.com/trenchboot1/3mdeb/linux/-/commits/linux-sl-5.5)

On the purposes of the TrenchBoot, linux kernel uses SECURE_LAUNCH module.

## Documentation

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.

## Continuous Integration

- basic building
- NixOS package building
- debian package building
