# Sample Apps for using Hyperledger Fabric on Kaleido

This repository contains 2 sample apps that demonstrate interacting with a Hyperledger Fabric network provisioned in Kaleido:

- written in golang using the `fabric-sdk-go` module: go to the [golang](./golang) folder
- written in node.js using the `fabric-sdk-node` modules: go to the [node.js](./node.js) folder
- written in Java using the `fabric-sdk-java` library: go to the [jdk](./jdk) folder

Note that once you compile the ChainCode (SmartContract) in Kaleido...then you can access it easily through a REST API.
ALternatively, if you want you can access the ChainCode directly using the normal Hyperledger Fabric SDKs.

So it might be an idea to be able to do both, so that moving to another hosted Blockchain we can run our client calls to the SDKs also.
