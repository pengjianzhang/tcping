# tcping [![Apache V2 License](https://img.shields.io/badge/license-Apache%20V2-blue.svg)](https://github.com/pengjianzhang/tcping/blob/main/LICENSE)

tcping is an easy-to-use syn packet detection tool.

## Compile
make

## Usage

iptables -t filter -I OUTPUT -p tcp  --tcp-flags RST RST -j DROP

tcping dev sip dip dport [num]

## License

tcping is distributed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
