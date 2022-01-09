# ascon
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/ascon/blob/master/LICENSE.md) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/ascon?status.png)](http://godoc.org/github.com/pedroalbanese/ascon)
[![GitHub downloads](https://img.shields.io/github/downloads/pedroalbanese/ascon/total.svg?logo=github&logoColor=white)](https://github.com/pedroalbanese/ascon/releases)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/ascon)](https://goreportcard.com/report/github.com/pedroalbanese/ascon)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/ascon)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/ascon)](https://github.com/pedroalbanese/ascon/releases)  

Ascon is a new family of authenticated encryption algorithms, submitted to the CAESAR competition for authenticated ciphers. The Ascon family was designed to be lightweight and easy to implement, even with added countermeasures against side-channel attacks. 
### Command-line Ascon v1.2 Encryption Tool
<pre>Usage of ascon:
ascon [-d] -p "pass" [-i N] [-s "salt"] -f &lt;file.ext&gt;
  -d    Decrypt instead Encrypt.
  -f string
        Target file. ('-' for STDIN)
  -i int
        Iterations. (for PBKDF2) (default 1024)
  -k string
        128-bit key to Encrypt/Decrypt.
  -p string
        PBKDF2.
  -r    Generate random 128-bit cryptographic key.
  -s string
        Salt. (for PBKDF2)</pre>

## License

This project is licensed under the ISC License.

##### Industrial-Grade Reliability. Copyright (c) 2020-2022 ALBANESE Research Lab.
