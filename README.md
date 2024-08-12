# Rust Bootcamp

Welcome to the Rust Bootcamp! This comprehensive guide will take you from a beginner to an advanced Rust programmer. Whether you're new to programming or already have experience with other languages, this bootcamp will equip you with the knowledge and skills to write efficient and reliable code in Rust.

## Important Links

1. [Bootcamp Notes](https://bootcampnotes.xyz/solana/)
2. [Slido Q/A](https://app.sli.do/event/gnixvMEio3qxHkitBTzcY9/live/questions)

## Table of Contents

1. [Getting Started](#getting-started)
2. [Solana keypair](#solana-keypair)

## Getting Started

To begin your Rust journey, you'll need to install the Rust programming language on your machine. Follow the official Rust installation guide for your operating system [here](https://www.rust-lang.org/tools/install).

Once Rust is installed, you can create a new Rust project using the `cargo` command-line tool:

```bash
$ cargo my_project
$ cd my_project
```

## Solana Keypair
```bash
solana-keygen new -o dev-sol-wallet/kp.json
```

NOTE! This BIP39 passphrase improves security of the recovery seed phrase NOT the
keypair file itself, which is stored as insecure plain text.

Wrote new keypair to `dev-sol-wallet/kp.json`

```
pubkey: 2EVTK5WauqhPN2iRq9ygWtHTSPvvHX6iJCY8fHTq8Mow
```

Save this seed phrase and your BIP39 passphrase to recover your new keypair:
`worry sock sorry illegal brother eyebrow boss symbol hidden quick cousin script`