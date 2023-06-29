# CertoraInit

CertoraInit Repository

* General Specifications - can be applied on included contracts or on any other desired solidity contract

* Ready to go configuration files - for your first verification report generated by the Certora Prover

This repository provides a fully functional skeleton for integrating with Certora.
Please note that formal verification can be highly resource intensive, and complex proofs may quickly become intractable.
A community of experts exists which can help guide you.
We welcome you to [contact us](XXX) for help integrating formal methods into your project.

## Through CI

The workflow file in this repository is completely integrated with Certora.
To see an example of the output of formal verification, see the Github checks on this repository.

This skeleton may also be used as a starting point for adding formal verification to another project.
You will need to provide your secret `CERTORAKEY` to Github, which can be obtained [here](XXX).

## From the Command Line

To run the checks from the command line, install the Python SDK and run from this directory:

```bash
certora verify
```
