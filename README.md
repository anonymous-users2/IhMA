This is a temprorey repository containing an implementation of our submitted paper Aggregate Signatures with Versatile Randomization:
Issuer-Hiding Multi-Authority Anonymous Credentials.
# Warning:
This implementation not been audited and is not ready for a production application. The library is provided for research-purpose only and is still not meant to be used in production.

#  Dependencies
Library is built on top of [petlib](https://github.com/gdanezis/petlib) and [bplib ](https://github.com/gdanezis/bplib), make sure to follow these instructions to install all the pre-requisites.

# Getting started
To install the development dependencies run
1. Install nix with the required experimental features from determinate systems

           curl --proto '=https' --tlsv1.2 -sSf -L https://install.determinate.systems/nix | sh -s -- install
    
2. Run: 
            
            nix develop

This will activate the development environment with the required dependencies.

# Run tests with nix

To run the tests in a precisely defined python environment using Nix 
         
         nix develop -c pytest -s -v tests/


# Usage

An easy way to see how to use the library can be found on the tests. 



