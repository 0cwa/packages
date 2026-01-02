# Contributing to OpenMANET Packages

Modifications to the OpenMANET project is done through custom OpenWRT packages.  We only make minor changes to the OpenWRT source for our specific needs.  If you want to add custom functionality to our project it should be done through package contributions.

## Guidelines
1. Packages contributed by the community **must** use a `PKG_HASH` for versioning.  Git tags will not be accepted by community contributions.
2. Modifications to existing configurations or future areas of development will not be allowed.
3. Packages that fail building often are subject to removal from the repository.  Test your packages well.
4. Package contributions must support building on all targets that OpenMANET supports.

## Getting Started
Review the [OpenWRT Documentation](https://openwrt.org/docs/guide-developer/packages) on how to create packages.

