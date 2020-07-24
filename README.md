## PPCA: Privacy-Preserving Collision Avoidance for Autonomous Unmanned Aerial Vehicles

## Formal verification with ProVerif
The security properties of `PPCA` have been verified formally and experimentally by using the open-source tool <a href="https://prosecco.gforge.inria.fr/personal/bblanche/proverif/">ProVerif 2.01</a>, demonstrating enhanced security protection with respect to state-of-the-art approaches.

In order to test the security properties, download the file <a href="ppca.pv">ppca.pv</a> and run: `./proverif ppca.pv | grep "RESULT"`.
Further, in order to verify that the location is a strong secret (i.e. the attacker cannot launch offline guessing attacks on the location value), please follow the guidelines inside the code.

<p align="center">
  <img src="./img/proverif.png" alt="PPCA" width="700">
</p>

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
`PPCA` is released under the BSD 3-Clause <a href="LICENSE">license</a>.