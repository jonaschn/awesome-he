# Awesome Homomorphic Encryption [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of amazing Homomorphic Encryption libraries, software and resources.

## Contents

- [Libraries](#libraries)
- [Toolkits](#toolkits)
- [Applications](#applications)
- [Databases](#databases)
- [Resources](#resources)

## Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.

- [blyss](https://github.com/blyssprivacy/sdk) - Rust FHE library specialized for private information retrieval. Includes bindings to JS & Python.
- [cuFHE](https://github.com/vernamlab/cuFHE) - CUDA-accelerated Fully Homomorphic Encryption Library.
- [cuHE](https://github.com/vernamlab/cuHE) - GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs.
- [Cupcake](https://github.com/facebookresearch/Cupcake) - Facebook's Rust library for the (additive version of the) Fan-Vercauteren scheme.
- [cuYASHE](https://github.com/cuyashe-library/cuyashe) - Based on leveled fully HE scheme YASHE for GPGPUs.
- [fhEVM](https://github.com/zama-ai/fhevm) - Solidity library that enables confidential smart contracts on the Ethereum VM using FHE.
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816).
- [FINAL](https://github.com/KULeuven-COSIC/FINAL) - C++ FHE library based on [NTRU and LWE scheme](https://eprint.iacr.org/2022/074).
- [FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) - A header-only library implementing the Fan-Vercauteren scheme.
- <a name="HEAAN">[HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic.
- [HEAAN-Python](https://github.com/Huelse/HEAAN-Python) - Python binding for the [HEANN](#HEAAN) library.
- <a name="HElib">[HElib](https://github.com/HomEnc/HElib) - BGV scheme with bootstrapping and the Approximate Number CKKS scheme.
- [HEMat](https://github.com/K-miran/HEMat) - C++ implementation of matrix computation (addition, multiplication, and transposition) using [HEANN](#HEAAN).
- [krypto](https://github.com/kryptnostic/krypto) - C++ implementation of multivariate quadratic FHE.
- [Λ ○ λ](https://github.com/cpeikert/Lol) - "Lol" Haskell library for ring-based lattice cryptography that supports FHE.
- <a name="lattigo">[lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
- [libScarab](https://github.com/hcrypt-project/libScarab) - C library implementing a FHE scheme using large integers.
- [libshe](https://github.com/bogdan-kulynych/libshe) - Symmetric somewhat HE library based on DGHV scheme.
- <a name="SEAL">[Microsoft SEAL](https://github.com/microsoft/SEAL) - C++ FHE library implementing BFV and CKKS schemes.</a>
- [NFLlib](https://github.com/quarkslab/NFLlib) - NTT-based Fast Lattice library specialized on power-of-two polynomials.
- [node-seal](https://github.com/morfix-io/node-seal) - JavaScript/WebAssembly port of [Microsoft SEAL](#SEAL).
- [NuFHE](https://github.com/nucypher/nufhe) - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe](#tfhe) algorithms.
- <a name="OpenFHE">[OpenFHE](https://github.com/openfheorg/openfhe-development) - C++ FHE library implementing all major schemes along with bootstrapping and scheme switching.
- <a name="OpenFHE-Python">[OpenFHE-Python](https://github.com/openfheorg/openfhe-python) - Python wrapper for [OpenFHE](#OpenFHE).
- <a name="OpenFHE-Rust">[OpenFHE-Rust](https://github.com/fairmath/openfhe-rs) - Rust wrapper for [OpenFHE](#OpenFHE).
- <a name="PALISADE">[PALISADE](https://palisade-crypto.org/software-library) - lattice encryption library (superseded by [OpenFHE](#OpenFHE)).
- [petlib](https://github.com/gdanezis/petlib) - Python library that implements a number of Privacy Enhancing Technologies.
- [PhantomFHE](https://github.com/encryptorion-lab/phantom-fhe) - A CUDA-Accelerated Fully Homomorphic Encryption Library.
- [Pyfhel](https://github.com/ibarrond/Pyfhel) - A Python wrapper for [SEAL](#SEAL), [HElib](#HElib), and [PALISADE](#PALISADE).
- [python-paillier](https://github.com/data61/python-paillier) - Partially HE based on Paillier scheme.
- [SEAL-python](https://github.com/Huelse/SEAL-Python/) - Python binding for the [Microsoft SEAL](#SEAL) library.
- [SparkFHE](https://github.com/SpiRITlab/spark) - Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
- [Sunscreen](https://github.com/Sunscreen-tech/Sunscreen) - Rust compiler for the BFV fully homomorphic encryption scheme.
- [TenSEAL](https://github.com/OpenMined/TenSEAL) - Library for HE operations on tensors, built on [Microsoft SEAL](#SEAL), with a Python API.
- <a name="tfhe">[tfhe](https://github.com/tfhe/tfhe) - Faster fully HE: Bootstrapping in less than 0.1 seconds.</a>
- [TFHE-rs](https://github.com/zama-ai/tfhe-rs) - Rust implementation of the TFHE scheme for boolean and integers FHE arithmetics by [Zama](https://github.com/zama-ai).

## Toolkits

- [ALCHEMY](https://github.com/cpeikert/ALCHEMY) - Haskell-based DSLs and interpreters/compilers, build on top of the lattice crypto library Lol.
- [AWS HE toolkit](https://github.com/awslabs/homomorphic-implementors-toolkit) - Simplifies the process of designing circuits for the CKKS scheme.
- [Cingulata](https://github.com/CEA-LIST/Cingulata) - Compiler toolchain and RTE for running C++ programs over encrypted data.
- [Concrete](https://github.com/zama-ai/concrete) - TFHE compiler for converting Python programs into FHE equivalents.
- [Concrete-ML](https://github.com/zama-ai/concrete-ml) - Python-based toolkit for data scientists w/o prior FHE knowledge (using sklearn, pyTorch, XGBoost models). 
- [E3](https://github.com/momalab/e3) - Encrypt-Everything-Everywhere framework for compiling C++ programs with encrypted operands.
- [EVA](https://github.com/microsoft/EVA) - A compiler and optimizer for the CKKS scheme (targeting [Microsoft SEAL](#SEAL)).
- [Google's FHE Repository](https://github.com/google/fully-homomorphic-encryption) - A compiler that converts a subset of C++ programs into FHE circuits implemented in various backend libraries (superseded by [HEIR](#HEIR)).
- <a name="HEIR">[HEIR](https://github.com/google/heir) - Google's MLIR-based toolchain for FHE compilers.
- [IBM HElayers](https://github.com/IBM/helayers) - IBM's FHE SDK for practical and efficient execution of encrypted workloads.
- [Marble](https://github.com/MarbleHE/Marble) - C++ framework that translates between nearly plaintext-style user programs and FHE computations.
- [SHEEP](https://github.com/alan-turing-institute/SHEEP) - HE evaluation platform with a set of native benchmarks and a library agnostic language.
- [T2](https://github.com/TrustworthyComputing/T2-FHE-Compiler-and-Benchmarks) - A cross compiler and standardized benchmarks for FHE computation that targets [lattigo](#lattigo), [HElib](#HElib), [PALISADE](#PALISADE), [Microsoft SEAL](#SEAL), and [tfhe](#tfhe).

## Applications

- [crypto-geofence](https://github.com/Georeactor/crypto-geofence) - Geo-fencing demo application based on Paillier scheme.
- [lattigo-polls](https://github.com/ldsec/lattigo-polls-demo) - Web-application for scheduling meetings using [lattigo](#lattigo).
- [Morfix.io](https://morfix.io/sandbox) - Web-based UI to play around with the [Microsoft SEAL](#SEAL) library.
- [nGraph-HE](https://github.com/IntelAI/he-transformer) - Deep Learning (DL) with HE through Intel’s DL graph compiler nGraph based on [SEAL](#SEAL).
- [OpenFHE demo applications](https://github.com/openfheorg/openfhe-development) - Several demo applications that demonstrate some of the capabilities of OpenFHE
  - [boolean-circuit-evaluator](https://github.com/openfheorg/openfhe-boolean-circuit-evaluator) - Demonstration application to read in boolean circuits using multiple formats and execute them in encrypted form based on binfhe module for encrypted boolean logic.
  - [genomic-examples](https://github.com/openfheorg/openfhe-genomic-examples) - Prototypes for secure genome-wide association studies using homomorphic encryption.
  - [logreg-training-examples](https://github.com/openfheorg/openfhe-logreg-training-examples) - Logistic Regression Training Examples.
- [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE and deep / federated learning.
  - [KotlinSyft](https://github.com/OpenMined/KotlinSyft) - Kotlin library for the Android part of the OpenMined's open-source ecosystem.
  - [PySyft](https://github.com/OpenMined/PySyft) - Python library for the server/IoT part of the OpenMined's open-source ecosystem.
  - [SwiftSyft](https://github.com/OpenMined/SwiftSyft) - Swift library for the iOS part of the OpenMined's open-source ecosystem.
  - [syft.js](https://github.com/OpenMined/syft.js) - JavaScript library for the web part of the OpenMined's open-source ecosystem.
- [Rosetta](https://github.com/LatticeX-Foundation/Rosetta) - A privacy-preserving framework based on TensorFlow.
- [tf-encrypted](https://github.com/tf-encrypted/tf-encrypted) - Bridge between TensorFlow and the [Microsoft SEAL](#SEAL) library.
- [Zama's Hugging Face spaces](https://huggingface.co/zama-fhe) - Demo apps showing the power of FHE for real-world use cases.

## Databases

- [CryptDB](https://github.com/CryptDB/cryptdb) - Protecting confidentiality with encrypted query processing.
- [encrypted-mongodb](https://github.com/pdroalves/encrypted-mongodb) - Wrapper on MongoDB's Python driver that enables to query encrypted data.
- [Prisma/DB](https://github.com/PrismaDB/PrismaDB) - Security layer for relational database systems.
- [TimeCrypt](https://github.com/TimeCrypt/timecrypt) - Encrypted time-series database using homomorphic encryption-based access control.
- [ZeroDB](https://github.com/zerodb/zerodb) - E2E encrypted database using proxy re-encryption.

## Resources

- [Barak, Boaz](https://intensecrypto.org/public/lec_15_FHE.html). Chapter about FHE in Barak's introductory book to Cryptography, used for Harvard CS 127.
- [Barthelemy, Lucas](https://blog.quarkslab.com/a-brief-survey-of-fully-homomorphic-encryption-computing-on-encrypted-data.html). Brief survey of Fully HE. 2016.
- [Chen, Zhigang](https://zhigang-chen.github.io/A%20List%20of%20FHE%20Papers.html). A continuously updated list of FHE papers.
- [FHE.org](https://fhe.org). A community of researchers and developers interested in advancing homomorphic encryption.
- [Gentry, Craig](https://crypto.stanford.edu/craig/craig-thesis.pdf). A fully homomorphic encryption scheme. Stanford University, 2009.
- [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government & academic consortium working on standardization of FHE.
- [KU Leuven](https://www.esat.kuleuven.be/cosic/tag/cosic-guide-to-crypto/). An introduction to homomorphic encryption.
- [Micciancio, Daniele](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
- [Microsoft Research](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn). Videos from SEAL/CKKS talks at Microsoft's Private AI Bootcamp.
- [OpenFHE](https://www.openfhe.org). Webinars about the foundations of applied FHE, the latest advances in the OpenFHE project and applications of FHE.
- [Vaikuntanathan, Vinoid](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.
- [Zhigang Chen](https://zhigang-chen.github.io/FHE%20Resources.html). A list of English and Chinese FHE and Machine Learning references.

## Related awesome lists

- [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography)
- [awesome-crypto-papers](https://github.com/pFarb/awesome-crypto-papers)
- [awesome-mpc](https://github.com/rdragos/awesome-mpc) - Multi-Party Computation.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Like this work?

✨ Star this project on GitHub [![GitHub Repo stars](https://img.shields.io/github/stars/jonaschn/awesome-he?style=social)](https://github.com/jonaschn/awesome-he)

🚀 Contribute further [awesome HE](https://github.com/jonaschn/awesome-he/edit/master/README.md) projects

💸 Spare me some ~~coffee~~ tea 🍵 via [Paypal](https://www.paypal.me/JonathanSchneiderDE/3)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonathan Schneider has waived all copyright and
related or neighboring rights to this work.
