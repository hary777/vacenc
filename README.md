# vacenc

Hannob inspired me with his `vacdec` [https://github.com/hannob/vacdec]https://github.com/hannob/vacdec

Python script to encode something like EU Covid-19 vaccine certificate.

This script takes a string with python dictionary string as parameter and create output.png
It is reversed version of Hannobs's vacdec. You need to get own sample data.

## setup

You will need the python cbor2 and base45 packages. 
You can install them via your distribution or via pip:

```
pip install base45 cbor2
```

In your system you need qrencode. Exapmle for Fedora34.

```
dnf install qrencode
```

## usage

Run:

```
./vacenc sample_data.txt
```


