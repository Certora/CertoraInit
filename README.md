# CertoraInit

CertoraInit Repository

This repository provides a fully functional skeleton for integrating with Certora.
Please note that formal verification can be highly resource intensive, and complex proofs may quickly become intractable.
A community of experts exists which can help guide you.
We welcome you to contact us via <a href="https://discord.gg/KEvKTWBC" target="_blank">Discord Help-Desk channel</a> 
for help integrating formal methods into your project.

## Through CI

The workflow file in this repository is completely integrated with Certora.
To see an example of the output of formal verification, see the Github checks on this repository.

This skeleton may also be used as a starting point for adding formal verification to another project.
You will need to provide your secret `CERTORAKEY` to Github, 
which can be obtained by joining Certora Service, either through submitting an enquiry to ea@certora.com
or via our <a href="https://www.certora.com/payg/" target="_blank">web</a>.

## From the Command Line

Detailed guide for <a href="https://docs.certora.com/en/latest/docs/user-guide/getting-started/install.html" target="_blank">Certora Prover installation</a>.


To run the checks from the command line, install the Python SDK and Prover Tool and run from this directory:

certoraRun ./certora/conf/default.conf 

## CVL Examples
See more  <a href="https://github.com/Certora/Examples/tree/master/CVLByExamples" target="_blank">CVL specification general examples</a>.

## VSCode Extension
Try out our official Beta version of <a href="https://marketplace.visualstudio.com/items?itemName=Certora.vscode-certora-prover" target="_blank">VSCode Extension</a>, allowing easier and more convenient access to the impressive capabilities of the Certora Prover.
