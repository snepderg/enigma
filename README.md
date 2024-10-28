# Starfall Enigma Chat
* an OOP-driven project based on the infamous Enigma Machine from WWII for its use in field cryptography.
* Read more here: https://en.wikipedia.org/wiki/Enigma_machine

## Credit
- Project Founder: Snepderg
- Debugging, Network Handshake, Chat Application: Superlamaface

## About this Project

* The project is built on top of StarfallEX, a sandboxed GLua environment within Garry's Mod:
https://github.com/thegrb93/StarfallEx

* The code is driven by Kikito's Middleclass library to enable OOP within Lua environments.
https://github.com/kikito/middleclass

## How it works
* Starfall Enigma Chat utilizes a Class-based implementation of the Enigma Machine. It has an interchangable number of virtual rotors which are represented by a string of uppercase characters consisting of the letters of the alphabet. The machine follows the standard procedure that a mechanical Enigma machine would and even includes the 'double-stepping problem' by design.
https://www.cryptomuseum.com/people/hamer/files/double_stepping.pdf
