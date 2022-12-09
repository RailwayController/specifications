<!--
SPDX-FileCopyrightText: 2022 Sidings Media <contact@sidingsmedia.com>
SPDX-License-Identifier: CC-BY-SA-4.0
-->

# Commands

These specifications refer to ways in which data is exchanged between
nodes within the network as well as between the main control node and
clients. In general, clients will normally use the REST API to
communicate with the system but may make use of web sockets or the USB
interface of the main node.

For serial interfaces, e.g. I2C, UART, web sockets and TCP sockets
within the wireless mesh, all commands should follow the format
specified by [serial-command.abnf](./serial-command.abnf).

For clients communicating with the main control node via the REST API,
commands should be sent according to the specification deffined in
[openapi.yaml](./openapi.yaml).
