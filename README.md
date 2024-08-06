# ZoKrateslib
An extendended standard library to the official ZoKrates stdlib

> This repository is experimental. Use at your own risk ⚠

## Extended functionality:
- [x] ecc support for JubJub curve
- [ ] ecc signature with different hashing algorithms
- [ ] Poseidon2
- [ ] Schorr Signatures 
- [ ] ...

## Usage

1. In the repo's parent directory run following comand:
   ```bash
   $ docker run -it -v "$(pwd)"/zokrates_stdlib/stdlib:/home/zokrates/.zokrates/stdlib zokrates/zokrates:0.8.8
   ```