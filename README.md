<!--
SPDX-FileCopyrightText: 2022 Sidings Media <contact@sidingsmedia.com>
SPDX-License-Identifier: CC-BY-SA-4.0
-->

# Railway Controller - Specification

This repository contains the specifications for communication within the
railway controller network as well as between the network and client
devices.

## Formats

### OpenAPI

All HTTP REST APIs used by the project are documented using YAML files
in the OpenAPI 3 standard. You can find out more about the spec at 
[spec.openapis.org](https://spec.openapis.org/)

### ABNF

All not HTTP communication (i.e commands and responses) are documented
using Augmented Backus–Naur form as per [RFC
5234](https://datatracker.ietf.org/doc/html/rfc5234)

## Licence
This repo uses the [REUSE](https://reuse.software) standard in order to
communicate the correct licence for the file. For those unfamiliar with
the standard the licence for each file can be found in one of three
places. The licence will either be in a comment block at the top of the
file, in a `.license` file with the same name as the file, or in the
dep5 file located in the `.reuse` directory. If you are unsure of the
licencing terms please contact
[contact@sidingsmedia.com](mailto:contact@sidingsmedia.com?subject=Railway%20Controller%20Licence).
All files committed to this repo must contain valid licencing
information or the pull request can not be accepted.
