# rdf-proofs-circom

## Setup

```
git clone https://github.com/iden3/circom.git
cd circom
cargo build --release
cargo install --path circom
```

## Compile circom circuits to get R1CS and Wasm files for the BLS12381 curve

```shell
circom ${CIRCOM_SOURCE} --r1cs --wasm --prime bls12381 --output ../target
```
