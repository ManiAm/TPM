# Trusted Platform Module (TPM)

A reference covering the Trusted Platform Module — its internal architecture, cryptographic capabilities, the software stack that communicates with it, and hands-on labs for practical TPM 2.0 operations.

## Overview

| # | Topic | Description |
|----|-------------------------------------------------------|-------------|
| 01 | [Trusted Platform Module](docs/01-TPM-intro.md) | What a TPM is, cryptographic engines, key hierarchies, TPM 1.2 vs. 2.0, implementation types, and platform usage |
| 02 | [TPM Internals](docs/02-TPM-internals.md) | Key generation and derivation, Platform Configuration Registers (PCRs), sealing and binding, remote attestation |

## Software Stack

| # | Topic | Description |
|----|-------------------------------------------------------|-------------|
| 03 | [TPM 2.0 Software Stack](docs/03-TPM-software-stack.md) | tpm2-tss library layers (FAPI, ESAPI, SAPI, TCTI), tpm2-tools CLI, tpm2-abrmd resource manager, and other TPM libraries |

## Hands-On Labs

| # | Topic | Description |
|----|-------------------------------------------------------|-------------|
| 04 | [TPM 2.0 Lab Setup](docs/04-TPM-lab-setup.md) | Environment choices (hardware, software, virtual TPM), TPM detection on Linux, Raspberry Pi, Windows, and WSL2, tool installation, software TPM setup |
| 05 | [TPM 2.0 Lab Exercises](docs/05-TPM-lab-exercises.md) | Progressive exercises — discovery, PCR extend, key hierarchies, signing, encryption, sealing, attestation, and NV storage |
