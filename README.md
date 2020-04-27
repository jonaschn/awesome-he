# Awesome Homomorphic Encryption [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


> A curated list of amazing Homomorphic Encryption libraries, software and resources.


## Contents

- [Libraries](#libraries)
- [Software](#software)
- [Databases](#databases)
- [Resources](#resources)


## Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.

- [cuHE](https://github.com/vernamlab/cuHE) - GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs.
- [cuFHE](https://github.com/vernamlab/cuFHE) - CUDA-accelerated Fully Homomorphic Encryption Library.
- [cuYASHE](https://github.com/cuyashe-library/cuyashe) - Based on leveled fully HE scheme YASHE for GPGPUs.
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816).
- [FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) - A header-only library implementing the Fan-Vercauteren scheme.
- [HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic.
- <a name="HElib">[HElib](https://github.com/HomEnc/HElib) - Brakerski-Gentry-Vaikuntanathan (BGV) scheme.
- [krypto](https://github.com/kryptnostic/krypto) - C++ implementation of multivariate quadratic FHE.
- [Λ ○ λ](https://github.com/cpeikert/Lol) - "Lol" Haskell library for ring-based lattice cryptography that supports FHE.
- [lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
- [libScarab](https://github.com/hcrypt-project/libScarab) - C library implementing a FHE scheme using large integers.
- [libshe](https://github.com/bogdan-kulynych/libshe) - Symmetric somewhat HE library based on DGHV scheme.
- [NFLlib](https://github.com/quarkslab/NFLlib) - NTT-based Fast Lattice library specialized on power-of-two polynomials.
- [NuFHE](https://github.com/nucypher/nufhe) - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe](#tfhe) algorithms.
- <a name="PALISADE">[PALISADE](https://git.njit.edu/palisade/PALISADE) - lattice encryption library.
- [petlib](https://github.com/gdanezis/petlib) - Python library that implements a number of Privacy Enhancing Technologies.
- [Pyfhel](https://github.com/ibarrond/Pyfhel) - A Python wrapper for [SEAL](#SEAL), [HElib](#HElib), and [PALISADE](#PALISADE).
- [python-paillier](https://github.com/n1analytics/python-paillier) - Partially HE based on Paillier scheme.
- <a name="SEAL">[SEAL](http://sealcrypto.org) - "FullRNS" optimization of Fan-Vercauteren scheme.</a>
- [SparkFHE](https://github.com/SpiRITlab/spark) - Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
- <a name="tfhe">[tfhe](https://github.com/tfhe/tfhe) - Faster fully HE: Bootstrapping in less than 0.1 seconds.</a>


## Software

- [ALCHEMY](https://github.com/cpeikert/ALCHEMY) - Haskell-based DSLs and interpreters/compilers, build on top of the lattice crypto library Lol.
- [Cingulata](https://github.com/CEA-LIST/Cingulata) - Compiler toolchain and RTE for running C++ programs over encrypted data.
- [crypto-geofence](https://github.com/Georeactor/crypto-geofence) - Geo-fencing demo application based on Paillier scheme.
- [nGraph-HE](https://github.com/NervanaSystems/he-transformer) - Deep Learning (DL) with HE through Intel’s DL graph compiler nGraph based on [SEAL](#SEAL).
- [Marble](https://github.com/MarbleHE/Marble) - A C++ framework that translates between nearly plaintext-style user programs and FHE computations.
- [MORFIX Sandbox](https://morfix.io/sandbox) - Web-based UI to play around with the [SEAL](#SEAL) library.
- [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE, blockchain and deep / federated learning.
- [SHEEP](https://github.com/alan-turing-institute/SHEEP) - HE evaluation platform with a set of native benchmarks and a library agnostic language.

## Databases

- [CryptDB](https://github.com/CryptDB/cryptdb) - Protecting confidentiality with encrypted query processing.
- [encrypted-mongodb](https://github.com/pdroalves/encrypted-mongodb) - Wrapper on MongoDB's Python driver that enables to query encrypted data.
- [Prisma/DB](https://github.com/PrismaDB/PrismaDB) - Security layer for relational database systems.
- [TimeCrypt](https://github.com/TimeCrypt/timecrypt) - Encrypted time-series database using homomorphic encryption-based access control.
- [ZeroDB](https://github.com/zerodb/zerodb) - E2E encrypted database using proxy re-encryption.


## Resources

- [Barthelemy, Lucas](https://blog.quarkslab.com/a-brief-survey-of-fully-homomorphic-encryption-computing-on-encrypted-data.html). Brief survey of Fully HE. 2016.
- [Daniele Micciancio](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
- [Gentry, Craig](https://crypto.stanford.edu/craig/craig-thesis.pdf). A fully homomorphic encryption scheme. Stanford University, 2009.
- [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government & academic consortium working on standardization of FHE.
- [KU Leuven](https://www.esat.kuleuven.be/cosic/tag/cosic-guide-to-crypto/). An introduction to homomorphic encryption.
- [Vinoid Vaikuntanathan](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.


## Related awesome lists

- [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography)
- [awesome-crypto-papers](https://github.com/pFarb/awesome-crypto-papers)
- [awesome-mpc](https://github.com/rdragos/awesome-mpc) - Multi-Party Computation.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonathan Schneider has waived all copyright and
related or neighboring rights to this work.
