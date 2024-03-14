# CertoraInit

This repository provides a fully functional skeleton for integrating with Certora.
Please note that formal verification can be highly resource intensive, and complex proofs may quickly become intractable.
A community of experts exists that can help guide you.
We welcome you to contact us via <a href="https://discord.gg/certora" target="_blank">Discord Help-Desk channel</a> 
for help integrating formal methods into your project.

To use this repository, `solc` on your machine must point a Solidity compiler of version 0.8.0 or higher.

## Through CI

The workflow file in this repository is completely integrated with Certora.
To see an example of the output of formal verification, see the GitHub checks on this repository.

This skeleton may also be used as a starting point for adding formal verification to another project.
You will need to provide your secret `CERTORAKEY` to GitHub, 
which can be obtained by joining Certora Service, either through submitting an inquiry to ea@certora.com
or via our <a href="https://www.certora.com/payg/" target="_blank">web form</a>.

## From the Command Line

To run the checks from the command line, first install the Python SDK:
`pip install certora-cli`
Then run from this directory:
`certoraRun ./certora/conf/default.conf`
If you encounter problems or have questions, please read our detailed <a href="https://docs.certora.com/en/latest/docs/user-guide/getting-started/install.html" target="_blank">installation guide</a>.

## CVL Examples
See more <a href="https://github.com/Certora/Examples/tree/master/CVLByExample" target="_blank">CVL specification general examples</a>.

## VSCode Extension
Try out our official Beta version of <a href="https://marketplace.visualstudio.com/items?itemName=Certora.vscode-certora-prover" target="_blank">VSCode Extension</a>, allowing easier and more convenient access to the impressive capabilities of the Certora Prover.

## Mutation Testing
The Certora Prover is integrated with <a href=https://www.certora.com/gambit>Gambit</a>, an open-source Solidity mutation testing tool. Mutation testing can give you an estimate of the coverage of your verification.

To run the mutation test from this directory, run `certoraMutate --conf certora/conf/default.conf`

The advanced example `certora/conf/advanced_mutation.conf` includes several advanced features of mutation tests, such as restricting mutation types and a manually crafted mutation. Please read the <a href="https://docs.certora.com/en/latest/docs/gambit/gambit.html" target="_blank">Gambit</a> mutation to learn more.
