# ProBook-4520s
Configs &amp; patches for running FreeBSD


`# kldload acpi_call`

set fan speed 0-99 fast->slow
```sh
# acpi_call -p '\_SB.PCI0.LPCB.EC0.SFSD' -i 1
```

get current fans spped
```sh
# acpi_call -p '\_SB.PCI0.LPCB.EC0.KRFS' -v
```
