# External dependencies of Apollo components

This is the BOM pacakage for all Apollo components. It contains all external libraries that are used by Apollo Java components. This package should be build and installed before all other packages.

## Components that user Apollo-bom-ext

1. [Apollo](https://github.com/ApolloFoundation/Apollo) Apollo blockchain node.
2. [Apollo-dektop](https://github.com/ApolloFoundation/Apollo-desktop) Desktop wallet UI. Apollo-web-ui must be installed tobe able to run Apollo desktop wallet.
3. [Apollo-tools](https://github.com/ApolloFoundation/Apollo-tools): "swiss knife" of tools for node maintenance, transaction signing, etc.


## Java version

Java 11 is required to build this module. For details, please read "Java version" section of [Apollo README](https://github.com/ApolloFoundation/Apollo)

## How to build it 

`./mvnw clean install`


## GIT branches

We follow GIT FLOW procedure in our developemnt and use following branhces:

__master__ branch contains stable code of the latest release. It is also tagged for each public release. Please see "Tags" in the "barcnh" dropdown menu. Plea
se use this branch to compile Apollo components.

__develop__ branch contains latest development version. Use this branch if you are developer/contributor.

__stage__ branch contains release preparation work of the last release. Do not use this branch if you are not release engineer


fix/*, feature/*, bugfix/** - temporary branches used by developers. Ususaly those branmches get merged to ___develop___ and deleted after work is done.