# Awesome Privacy Computing

# 1 Secure Multiparty Computation (SMPC)

### 1.1 Primitive

#### 1.1.1 Oblivious Transfer (OT)

- [Precomputing Oblivious Transfer, CRYPTO'95](https://link.springer.com/content/pdf/10.1007%2F3-540-44750-4_8.pdf), Bea95
- [Efficient Oblivious Transfer Protocols, SODA'01](https://dl.acm.org/doi/10.5555/365411.365502), NP01
- [Extending Oblivious Transfers Efficiently, CRYPTO'03](http://link.springer.com/10.1007/978-3-540-45146-4_9), IKNP03
- [More Efficient Oblivious Transfer and Extensions for Faster Secure Computation, CCS'13](https://eprint.iacr.org/2013/552.pdf), [slide](https://www.cs.cornell.edu/~asharov/slides/ALSZ13.pdf), ALSZ13
- [Improved OT Extension for Transferring Short Secrets, CRYPTO'13](https://eprint.iacr.org/2013/491.pdf), KK13
- [Actively Secure OT Extension with Optimal Overhead, CRYPTO'15](https://eprint.iacr.org/2015/546.pdf), KOS15
- [MASCOT: Faster Malicious Arithmetic Secure Computation with Oblivious Transfer, CCS'16](https://eprint.iacr.org/2016/505.pdf)
- [Fast Actively Secure OT Extension for Short Secrets, NDSS'17](http://arxiv.org/abs/1911.08834), [slide](https://www.ndss-symposium.org/wp-content/uploads/2017/09/ndss2017_04B-1-suresh-slides.pdf), [video](https://youtu.be/urV3ljX-DqQ)
- [Efficient Pseudorandom Correlation Generators: Silent OT Extension and More, CRYPTO'19](https://eprint.iacr.org/2019/448.pdf)
- [Efficient two-round OT extension and silent non-interactive secure computation, CCS'19](https://eprint.iacr.org/2019/1159.pdf)
- [Ferret: Fast Extension for Correlated OT with Small Communication, CCS'20](https://eprint.iacr.org/2020/924.pdf)
- [Silver: Silent VOLE and Oblivious Transfer from Hardness of Decoding Structured LDPC Codes, CRYPTO'21](https://eprint.iacr.org/2021/1150.pdf)

#### 1.1.2 Garbled Circuit

- [Protocols for Secure Computations (Extended Abstract), FOCS'82](https://crysp.uwaterloo.ca/courses/pet/F11/cache/www.cs.wisc.edu/areas/sec/yao1982-ocr.pdf)
- [How to generate and exchange secrets, FOCS'86](https://dl.acm.org/doi/pdf/10.1145/266420.266424)
- [Improved Garbled Circuit: Free XOR Gates and Applications, ICALP'08](http://www.cs.toronto.edu/~vlad/papers/XOR_ICALP08.pdf)
- [FairplayMP – A System for Secure Multi-Party Computation, CCS'08](https://www.cs.huji.ac.il/~noam/FairplayMP.pdf)
- [Secure Two-Party Computation Is Practical, ASIACRYPT'09](https://eprint.iacr.org/2009/314.pdf)
- [Foundations of Garbled Circuits, CCS'12](https://eprint.iacr.org/2012/265.pdf)
- [FleXOR: Flexible Garbling for XOR Gates That Beats Free-XOR, CRYPTO'14](https://eprint.iacr.org/2014/460.pdf)
- [Two Halves Make a Whole: Reducing Data Transfer in Garbled Circuits using Half Gates, EUROCRYPT'15](https://eprint.iacr.org/2014/756.pdf)
- [Fast and Secure Three-party Computation: The Garbled Circuit Approach, CCS'15](https://eprint.iacr.org/2015/931.pdf)
- [Three Halves Make a Whole? Beating the Half-Gates Lower Bound for Garbled Circuits, CRYPTO'21](https://eprint.iacr.org/2021/749.pdf)

#### 1.1.3  Arithmetic/Boolean Circuit

- [How to play ANY mental game, STOC'87](https://www.researchgate.net/publication/234778924_How_to_play_ANY_mental_game/link/0deec5232112523fc5000000/download), GMW
- [Scalable and unconditionally secure multiparty computation, CRYPTO'07](https://www.iacr.org/archive/crypto2007/46220565/46220565.pdf)
- [Perfectly-secure MPC with linear communication complexity, TCC'08](https://link.springer.com/chapter/10.1007/978-3-540-78524-8_13) 
- [Sharemind: A framework for fast privacy-preserving computations, ESORICS'08](https://link.springer.com/chapter/10.1007/978-3-540-88313-5_13)
- [Multiparty Computation from Somewhat Homomorphic Encryption, IACR ePrint'11](https://eprint.iacr.org/2011/535.pdf)
- [Practical Covertly Secure MPC for Dishonest Majority Or: Breaking the SPDZ Limits, ESORICS'13](https://eprint.iacr.org/2012/642.pdf) 
- [High-Throughput Semi-Honest Secure Three-Party Computation with an Honest Majority, CCS'16](https://dl.acm.org/citation.cfm?id=2978331)
- [High-throughput secure three-party computation for malicious adversaries and an honest majority, CRYPTO'17](https://eprint.iacr.org/2016/944.pdf)
- [A Framework for Constructing Fast MPC over Arithmetic Circuits with Malicious Adversaries and an Honest-Majority, CCS'17](https://eprint.iacr.org/2017/816.pdf)
- [SPDZ2k: Efficient MPC mod 2k for Dishonest Majority, CRYPTO'18](https://eprint.iacr.org/2018/482.pdf)
- [Yet another compiler for active security or: Efficient MPC over arbitrary rings, CRYPTO'18](https://eprint.iacr.org/2017/908)
- [Overdrive^2k: Making SPDZ Great Again, Eurocrypto'18](https://eprint.iacr.org/2017/1230)
- [An end-to-end system for large scale P2P MPC-as-a-service and low-bandwidth MPC for weak participants, CCS'18](https://eprint.iacr.org/2018/751.pdf)
- [Fast large-scale honest-majority MPC for malicious adversaries, CRYPTO'18](https://eprint.iacr.org/2018/570)
- [Minimising communication in honest-majority MPC by batchwise multiplication verification, ACNS'18](https://eprint.iacr.org/2018/474)
- [Two-thirds honest-majority MPC for malicious adversaries at almost the cost of semi-honest, CCS'19](https://dl.acm.org/doi/10.1145/3319535.3339811)
- [Efficient Information-Theoretic Secure Multiparty Computation over Z/pkZ via Galois Rings, TCC'19](https://eprint.iacr.org/2019/872)
- [Malicious Security Comes Free in Honest-Majority MPC, IACR ePrint'20](https://eprint.iacr.org/2020/134)
- [Use Your Brain! Arithmetic 3PC for Any Modulus with Active Security, ITC'20](https://eprint.iacr.org/2019/164.pdf)
- [ATLAS: Efficient and Scalable MPC in the Honest Majority Setting, CRYPTO'21](https://eprint.iacr.org/2021/833)
- [The Cost of IEEE Arithmetic in Secure Computation, LatinCrypt'21](https://eprint.iacr.org/2021/054)
- [Rabbit: Efficient Comparison for Secure Multi-Party Computation, FC'21](https://eprint.iacr.org/2021/119)
- [Honest Majority MPC with Abort with Minimal Online Communication, Latincrypt'21](https://eprint.iacr.org/2020/1556)
- [CostCO: An automatic cost modeling framework for secure multi-party computation, Euro S&P'22](https://eprint.iacr.org/2022/332)
- [Fast Fully Secure Multi-Party Computation over Any Ring with Two-Thirds Honest Majority, CCS'22](https://eprint.iacr.org/2022/623)
- [More Efficient Dishonest Majority Secure Computation over Z2k via Galois Rings, CRYPTO'22](https://eprint.iacr.org/2022/815.pdf)

#### 1.1.5 A/B/Y Shares Conversion

- [ABY: A Framework for Effificient Mixed-Protocol Secure Two-Party Computation, NDSS'15](https://encrypto.de/papers/DSZ15.pdf)
- [ABY3: A Mixed Protocol Framework for Machine Learning, CCS'18](https://eprint.iacr.org/2018/403.pdf)
- [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2019/1315)
- [MP-SPDZ: A versatile framework for multi-party computation, CCS'20](https://eprint.iacr.org/2020/521.pdf)
- [Improved primitives for mpc over mixed arithmetic-binary circuits, CRYPTO'20](https://eprint.iacr.org/2020/338.pdf)
- [ABY2.0: Improved Mixed-Protocol Secure Two-Party Computation, USENIX Security'21](https://eprint.iacr.org/2020/1225.pdf)
- [MOTION – A Framework for Mixed-Protocol Multi-Party Computation, TOPS'22](https://eprint.iacr.org/2020/1137)
- [Tetrad: Actively Secure 4PC for Secure Training and Inference, NDSS'22](https://arxiv.org/abs/2106.02850)


#### 1.1.6 PSI

- [Faster Private Set Intersection based on OT Extension, USENIX Security'14](https://eprint.iacr.org/2014/447.pdf), [code: PSI](https://github.com/encryptogroup/PSI)
- [Efficient Batched Oblivious PRF with Applications to Private Set Intersection, CCS'16](https://eprint.iacr.org/2016/799.pdf), [code: BaRK-OPRF](https://github.com/osu-crypto/BaRK-OPRF)
- [Actively Secure 1-out-of-N OT Extension with Application to Private Set Intersection, CT-RSA'17](https://eprint.iacr.org/2016/933.pdf)
- [Practical Multi-party Private Set Intersection from Symmetric-Key Techniques, CCS'17](https://eprint.iacr.org/2017/799.pdf), [code: MultipartyPSI](https://github.com/osu-crypto/MultipartyPSI)
- [Scalable Private Set Intersection Based on OT Extension, TOPS'18](https://eprint.iacr.org/2016/930.pdf)
- [Labeled PSI from Fully Homomorphic Encryption with Malicious Security, CCS'18](https://eprint.iacr.org/2018/787.pdf)
- [An Algebraic Approach to Maliciously Secure Private Set Intersection, EUROCRYPT'19](https://eprint.iacr.org/2017/1064.pdf)
- [SpOT-Light: Lightweight Private Set Intersection from Sparse OT Extension, CRYPTO'19](https://eprint.iacr.org/2019/634.pdf)
- [PSI from PaXoS: Fast, Malicious Private Set Intersection, EUROCRYPT'20](https://eprint.iacr.org/2020/193.pdf)
- [Private Set Intersection in the Internet Setting from Lightweight Oblivious PRF, CRYPTO'20](https://link.springer.com/content/pdf/10.1007/978-3-030-56877-1_2.pdf)
- [Labeled PSI from homomorphic encryption with reduced computation and communication, CCS'21](https://eprint.iacr.org/2021/1116.pdf)
- [Efficient Linear Multiparty PSI and Extensions to Circuit/Quorum PSI, CCS'21](https://eprint.iacr.org/2021/172.pdf)
- [VOLE-PSI: Fast OPRF and Circuit-PSI from Vector-OLE, EUROCRYPT'21](https://eprint.iacr.org/2021/266.pdf)
- [Private Set Operations from Oblivious Switching, PKC'21](https://eprint.iacr.org/2021/243.pdf)
- [Oblivious Key-Value Stores and Amplification for Private Set Intersection, CRYPTO'21](https://eprint.iacr.org/2021/883.pdf)
- [Circuit-PSI With Linear Complexity via Relaxed Batch OPPRF, PoPETS'22](https://petsymposium.org/2022/files/papers/issue1/popets-2022-0018.pdf)
- [LibPSI](https://github.com/osu-crypto/libPSI)

#### 1.1.7 Multiparty ECDSA signing
- [Fast Secure Multiparty ECDSA with Practical Distributed Key Generation and Applications to Cryptocurrency Custody, CCS'18](https://eprint.iacr.org/2018/987), [code: Blockchain-Crypto-MPC](https://github.com/unbound-tech/blockchain-crypto-mpc)
- [Threshold ECDSA from ECDSA Assumptions: The Multiparty Case, S&P'19](https://eprint.iacr.org/2019/523), [code: MPECDSA](https://gitlab.com/neucrypt/mpecdsa)

#### 1.1.8 Function Secret Sharing
- [Secure Computation with Preprocessing via Function Secret Sharing, TCC'19](https://link.springer.com/content/pdf/10.1007/978-3-030-36030-6_14.pdf)
- [Function Secret Sharing for Mixed-Mode and Fixed-Point Secure Computation, EUROCRYPT'21](https://link.springer.com/content/pdf/10.1007/978-3-030-77886-6_30.pdf)

## 1.2 Survey

- [Secure Multiparty Computation (MPC)](https://eprint.iacr.org/2020/300.pdf), Yehuda Lindell.
- [How to Simulate It - A Tutorial on the Simulation Proof Technique](https://eprint.iacr.org/2016/046.pdf), Yehuda Lindell.
- [Secure Multi-Party Computation](http://ebooks.iospress.com/volume/secure-multi-party-computation), Manoj Prabhakaran, Amit Sahai. 
- [An Introduction to Secret-Sharing-Based Secure Multiparty Computation](https://eprint.iacr.org/2022/062.pdf), Daniel Escudero. 
- [实用安全多方计算协议关键技术研究进展, 计算机研究与发展'15](https://crad.ict.ac.cn/CN/10.7544/issn1000-1239.2015.20150763)

## 1.3 Books

- [The Foundations of Cryptography - Volume 1: Basic Tools](https://www.wisdom.weizmann.ac.il/~oded/foc-vol1.html), Oded Goldreich. 2001. 
- [The Foundations of Cryptography - Volume 2: Basic Applications](http://www.wisdom.weizmann.ac.il/~oded/foc-vol2.html), Oded Goldreich. 2003.
- [Efficient secure two-party protocols: Techniques and constructions](https://www.springer.com/us/book/9783642143021), Carmit Hazay, Yehuda Lindell. 2010.
- [Engineering Secure Two-Party Computation Protocols](https://www.sites.google.com/site/thomaschneider/publications/engineeringsfebook), Thomas Schneider. 2012.
- [Secure Multiparty Computation and Secret Sharing](http://www.cambridge.org/dk/academic/subjects/computer-science/cryptography-cryptology-and-coding/secure-multiparty-computation-and-secret-sharing?format=HB), Ronald Cramer, Ivan Bjerre Damgård, Jesper Buus Nielsen. 2015.
- [Applications of Secure Multiparty Computation](http://ebooks.iospress.nl/volume/applications-of-secure-multiparty-computation), Peeter Laud, Liina Kamm. 2015.
- [A Pragmatic Introduction to Secure Multi-Party Computation](https://securecomputation.org/), David Evans, Vladimir Kolesnikov, Mike Rosulek. 2018.


## 1.4 Courses

- [Cryptographic Computing Course](http://orlandi.dk/crycom)
- [FHE-MPC Advanced Grad Course](https://homes.esat.kuleuven.be/~nsmart/FHE-MPC/)
- [Secure Computation](http://drona.csa.iisc.ernet.in/~arpita/SecureComputation15.html)
- [Secure Multi-Party Computation at Scale](https://piazza.com/bu/fall2017/cs591v1/home)
- [The 1st BIU Winter School on Secure Computation and Efficiency](https://cyber.biu.ac.il/event/the-1st-biu-winter-school/)
- [The 5th BIU Winter School on Advances in Practical Multiparty Computation](https://cyber.biu.ac.il/event/the-5th-biu-winter-school/)
- [The 12th BIU Winter School on Cryptography](https://cyber.biu.ac.il/event/the-12th-biu-winter-school-on-cryptography/)
- [The Universal Composability Framework](https://m.youtube.com/playlist?list=PLqc9MPlwib9nSuyH4oUIwPsyDiZ4bwuEE)


# 1.5 Open Source Framework

- [ABY](https://github.com/encryptogroup/ABY), [NDSS'15](http://encrypto.de/papers/DSZ15.pdf).
- [ABY3](https://github.com/ladnir/aby3), [CCS'18](https://eprint.iacr.org/2018/403.pdf), [2019/518](https://eprint.iacr.org/2019/518.pdf).
- [BatchDualEx](https://github.com/osu-crypto/batchDualEx), eprint: [2016/632](https://eprint.iacr.org/2016/632).
- [CrypTen](https://github.com/facebookresearch/CrypTen), [link](https://crypten.ai/)
- [EMP-toolkit](https://github.com/emp-toolkit),  (emp-[ag2pc|m2pc|agmpc]) | eprint: [2017/189](https://eprint.iacr.org/2017/189), [2016/762](https://eprint.iacr.org/2016/762), [2017/030](https://eprint.iacr.org/2017/030).
- [Fancy-Garbling](https://github.com/spaceships/fancy-garbling), [2016/969](https://eprint.iacr.org/2016/969).
- [FRESCO](http://fresco.readthedocs.io/en/latest/) , [Practice'15](http://practice-project.eu/downloads/publications/D22.1-State-of-the-art-analysis-PU-V1.1.pdf).
- [HoneyBadgerMPC](https://github.com/initc3/HoneyBadgerMPC)
- [JIFF](https://github.com/multiparty/jiff/), [link](https://multiparty.org/jiff/).
- [MP-SPDZ](https://github.com/data61/MP-SPDZ), [documentation](https://mp-spdz.readthedocs.io/en/latest/) | eprint: [2020/512](https://eprint.iacr.org/2020/521)
- [MPyC](https://www.win.tue.nl/~berry/mpyc/), [TPMPC'18](https://www.win.tue.nl/~berry/mpyc/TPMPC2018.pdf).
- [Obliv-C](http://oblivc.org/), [2015/1153](http://eprint.iacr.org/2015/1153).
- [SCALE-MAMBA](https://homes.esat.kuleuven.be/~nsmart/SCALE/), [link](https://homes.esat.kuleuven.be/~nsmart/SCALE/Documentation.pdf).
- [Sharemind](https://sharemind.cyber.ee/), [Cyber'13](https://cyber.ee/research/theses/roman_jagomagis_msc.pdf).
- [swanky](https://github.com/GaloisInc/swanky), [Tf-encrypted](https://github.com/mortendahl/tf-encrypted/)


# 2 Federated Learning (FL)

* [Privacy-Preserving Deep Learning, CCS'15](https://dl.acm.org/citation.cfm?id=2813687)
* [Practical Secure Aggregation for Privacy Preserving Machine Learning, CCS'17](https://eprint.iacr.org/2017/281.pdf)
* [Privacy-Preserving Deep Learning via Additively Homomorphic Encryption, TIFS'17](https://ieeexplore.ieee.org/document/8241854)
* [NIKE-based Fast Privacy-preserving High-dimensional Data Aggregation for Mobile Devices, CACR'18](http://cacr.uwaterloo.ca/techreports/2018/cacr2018-10.pdf)
* [PrivFL: Practical Privacy-preserving Federated Regressions on High-dimensional Data over Mobile Networks, CCSW'19](https://eprint.iacr.org/2019/979.pdf)
* [VerifyNet: Secure and verifiable federated learning, TIFS'19](https://ieeexplore.ieee.org/abstract/document/8765347)
* [PrivColl: Practical Privacy-Preserving Collaborative Machine Learning](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_20)
* [NPMML: A Framework for Non-interactive Privacy-preserving Multi-party Machine Learning, TDSC'20](https://ieeexplore.ieee.org/abstract/document/8981947)
* [SAFER: Sparse secure Aggregation for FEderated leaRning](https://arxiv.org/abs/2007.14861)
* [Secure Byzantine-Robust Machine Learning](https://arxiv.org/abs/2006.04747)
* [Secure Single-Server Aggregation with (Poly)Logarithmic Overhead, CCS'20](https://eprint.iacr.org/2020/704.pdf)
* [Batchcrypt: Efficient homomorphic encryption for cross-silo federated learning, USENIX ATC'21](https://www.usenix.org/conference/atc20/presentation/zhang-chengliang)
* [FedSel: Federated SGD under Local Differential Privacy with Top-k Dimension Selection, DASFAA'20](https://arxiv.org/abs/2003.10637)
* [FLGUARD: Secure and Private Federated Learning, Cryptology Eprint'21](https://eprint.iacr.org/2021/025)
* [Biscotti: A Blockchain System for Private and Secure Federated Learning, TPDS'21](https://ieeexplore.ieee.org/document/9292450)
* [POSEIDON: Privacy-Preserving Federated Neural Network Learning, NDSS'21](https://arxiv.org/abs/2009.00349)


# 3 Trusted Execution Environment (TEE)

# 4 Homomorphic Encryption (HE)

## 4.1 FHE Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.
- [Microsoft SEAL](https://github.com/microsoft/SEAL) - C++ FHE library implementing BFV and CKKS schemes.</a>
- [HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic.
- [HElib](https://github.com/HomEnc/HElib) - BGV scheme with bootstrapping and the Approximate Number CKKS scheme.
- [lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
- [PALISADE](https://palisade-crypto.org/software-library) - lattice encryption library.
- [tfhe](https://github.com/tfhe/tfhe) - Faster fully HE: Bootstrapping in less than 0.1 seconds.</a>
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816).
- [concrete](https://github.com/zama-ai/concrete) - Rust FHE library that implements Zama's variant of TFHE.
- [Cupcake](https://github.com/facebookresearch/Cupcake) - Facebook's Rust library for the (additive version of the) Fan-Vercauteren scheme.

## 4.2 FHE Applications
- [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE and deep / federated learning.
	- [KotlinSyft](https://github.com/OpenMined/KotlinSyft) - Kotlin library for the Android part of the OpenMined's open-source ecosystem.
	- [PySyft](https://github.com/OpenMined/PySyft) - Python library for the server/IoT part of the OpenMined's open-source ecosystem.
	- [SwiftSyft](https://github.com/OpenMined/SwiftSyft) - Swift library for the iOS part of the OpenMined's open-source ecosystem.
	- [syft.js](https://github.com/OpenMined/syft.js) - JavaScript library for the web part of the OpenMined's open-source ecosystem.
- [Rosetta](https://github.com/LatticeX-Foundation/Rosetta) - A privacy-preserving framework based on TensorFlow.
- [tf-encrypted](https://github.com/tf-encrypted/tf-encrypted) - Bridge between TensorFlow and the [Microsoft SEAL](#SEAL) library.

## 4.3 FHE Papers

- [Fully homomorphic encryption using ideal lattices, STOC'99](https://dl.acm.org/doi/10.1145/1536414.1536440).
- [Fully homomorphic encryption from ring-LWE and security for key dependent messages, CRYPTO'11](http://link.springer.com/10.1007/978-3-642-22792-9_29).
- [Homomorphic Evaluation of the AES Circuit, CRYPTO'12](https://link.springer.com/chapter/10.1007/978-3-642-32009-5_49).
- [Fully homomorphic encryption with polylog overhead, EUROCRYPT'12](https://link.springer.com/chapter/10.1007/978-3-642-29011-4_28).
- [Fully Homomorphic Encryption without Modulus Switching from Classical GapSVP, CRYPTO'12](http://link.springer.com/10.1007/978-3-642-32009-5_50).
- [Homomorphic Encryption from Learning with Errors: Conceptually-Simpler, Asymptotically-Faster, Attribute-Based, CRYPTO'13](http://link.springer.com/10.1007/978-3-642-40041-4_5)
- [Algorithms in HElib, CRYPTO'14](http://link.springer.com/10.1007/978-3-662-44371-2_31)
- [FHEW: Bootstrapping Homomorphic Encryption in Less Than a Second, EUROCRYPT'15](http://link.springer.com/10.1007/978-3-662-46800-5_24)
- [Faster Fully Homomorphic Encryption: Bootstrapping in Less Than 0.1 Seconds, ASIACRYPT'16](http://link.springer.com/10.1007/978-3-662-53887-6_1)
- [Faster packed homomorphic operations and efficient circuit bootstrapping for TFHE, ASIACRYPT'17](http://link.springer.com/10.1007/978-3-319-70694-8_14)
- [Homomorphic Encryption for Arithmetic of Approximate Numbers, ASIACRYPT'17](http://link.springer.com/10.1007/978-3-319-70694-8_15)
- [A Full RNS Variant of FV Like Somewhat Homomorphic Encryption Schemes, SAC'17](http://link.springer.com/10.1007/978-3-319-69453-5_23)
- [Faster packed homomorphic operations and efficient circuit bootstrapping for TFHE, ASIACRYPT'17](10.1007/978-3-319-70694-8_14)
- [Faster homomorphic linear transformations in HElib, CRYPTO'18](http://link.springer.com/10.1007/978-3-319-96884-1_4)
- [Bootstrapping for Approximate Homomorphic Encryption, EUROCRYPT'18](https://link.springer.com/chapter/10.1007/978-3-319-78381-9_14)
- [An Improved RNS Variant of the BFV Homomorphic Encryption Scheme, CT-RSA'19](http://link.springer.com/10.1007/978-3-030-12612-4_5)
- [TFHE: Fast Fully Homomorphic Encryption Over the Torus, JOC'20](http://link.springer.com/10.1007/s00145-019-09319-x)
- [Efficient Homomorphic Comparison Methods with Optimal Complexity, ASIACRYPT'20](https://link.springer.com/10.1007/978-3-030-64834-3_8)
- [PEGASUS: Bridging polynomial and non-polynomial evaluations in homomorphic encryption, S&P'21](https://ieeexplore.ieee.org/document/9519408/)
- [General Bootstrapping Approach for RLWE-based Homomorphic Encryption, ePrint'21](https://eprint.iacr.org/2021/691)
- [On the Security of Homomorphic Encryption on Approximate Numbers, EUROCRYPT'21](https://link.springer.com/10.1007/978-3-030-77870-5_23)
- [Efficient Bootstrapping for Approximate Homomorphic Encryption with Non-sparse Keys, EUROCRYPT'21](https://link.springer.com/10.1007/978-3-030-77870-5_21)
- [Efficient Homomorphic Conversion Between (Ring) LWE Ciphertexts, ACNS'21](https://link.springer.com/chapter/10.1007/978-3-030-78372-3_18)
- [OpenFHE: Open-Source Fully Homomorphic Encryption Library, ePrint'22](https://eprint.iacr.org/2022/915)
  
# 5 Differential Privacy (DP)

# 6 Zero-Knowledge Proof (ZKP)
- [简洁非交互零知识证明综述, 密码学报'22](http://www.jcr.cacrnet.org.cn/CN/Y2022/V9/I3/379)

# 7 Privacy-Preserving Machine Learning (PPML)

## 7.1 Papers
* [Machine Learning Classification over Encrypted Data, NDSS'14](https://eprint.iacr.org/2014/331.pdf)
* [Oblivious Multi-Party Machine Learning on Trusted Processors, USENIX SECURITY'16](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/ohrimenko)
* [CryptoNets: Applying Neural Networks to Encrypted Data with High Throughput and Accuracy, ICML'16](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/04/CryptonetsTechReport.pdf)
* [CryptoDL: Deep Neural Networks over Encrypted Data, arXiv'17](https://arxiv.org/abs/1711.05189)
* [Prio: Private, Robust, and Scalable Computation of Aggregate Statistics, NSDI'17](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/corrigan-gibbs)
* [SecureML: A System for Scalable Privacy-Preserving Machine Learning, S&P'17](https://eprint.iacr.org/2017/396)
* [MiniONN: Oblivious Neural Network Predictions via MiniONN Transformations, CCS'17](https://acmccs.github.io/papers/p619-liuA.pdf)
* [Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications, AsiaCCS'17](https://eprint.iacr.org/2017/1164)
* [DeepSecure: Scalable Provably-Secure Deep Learning, DAC'17](https://arxiv.org/abs/1705.08963)
* [Secure Computation for Machine Learning With SPDZ, NIPS'18](https://arxiv.org/abs/1901.00329)
* [PySyft: A Generic Framework for Privacy Preserving Deep Learning, arXiv'18](https://arxiv.org/abs/1811.04017)
* [ABY3: A Mixed protocol Framework for Machine Learning, CCS'18](https://eprint.iacr.org/2018/403.pdf)
* [SecureNN: Efficient and Private Neural Network Training, PoPETs'18](https://eprint.iacr.org/2018/442.pdf)
* [Gazelle: A Low Latency Framework for Secure Neural Network Inference, USENIX SECURITY'18](https://arxiv.org/abs/1801.05507)
* [Private Machine Learning in TensorFlow using Secure Computation, arXiv'18](https://arxiv.org/abs/1810.08130)
* [CHET: an optimizing compiler for fully-homomorphic neural-network inferencing, PLDI'19](https://dl.acm.org/citation.cfm?id=3314628)
* [New Primitives for Actively-Secure MPC over Rings with Applications to Private Machine Learning, S&P'19](https://eprint.iacr.org/2019/599.pdf)
* [Helen: Maliciously Secure Coopetitive Learning for Linear Models, S&P'19](https://ieeexplore.ieee.org/abstract/document/8835215)
* [Efficient multi-key homomorphic encryption with packed ciphertexts with application to oblivious neural network inference. CCS'19](https://dl.acm.org/citation.cfm?id=3363207)
* [XONN: XNOR-based Oblivious Deep Neural Network Inference, USENIX Security'19](https://www.usenix.org/conference/usenixsecurity19/presentation/riazi)
* [QUOTIENT: two-party secure neural network training and prediction, CCS'19](https://dl.acm.org/citation.cfm?id=3339819)
* [ASTRA: High Throughput 3PC over Rings with Application to Secure Prediction, CCSW'19](https://eprint.iacr.org/2019/429)
* [SoK: Modular and Efficient Private Decision Tree Evaluation, PoPETs'19](https://eprint.iacr.org/2018/1099.pdf)
* [Garbled Neural Networks are Practical, IACR ePrint'19](https://eprint.iacr.org/2019/338.pdf)
* [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2019/1315)
* [BLAZE: Blazing Fast Privacy-Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2020/042)
* [FLASH: Fast and Robust Framework for Privacy-preserving Machine Learning, PoPETs'20](https://eprint.iacr.org/2019/1365)
* [Secure Evaluation of Quantized Neural Networks, PoPETs'20](https://content.sciendo.com/view/journals/popets/2020/4/article-p355.xml)
* [Delphi: A Cryptographic Inference Service for Neural Networks, USENIX SECURITY'20](https://eprint.iacr.org/2020/050)
* [MP2ML: A Mixed-Protocol Machine Learning Framework for Private Inference, ARES'20](https://dl.acm.org/doi/abs/10.1145/3407023.3407045)
* [SANNS: Scaling Up Secure Approximate k-Nearest Neighbors Search, USENIX Security'20](https://www.usenix.org/conference/usenixsecurity20/presentation/chen-hao)
* [CrypTen: Secure multi-party computation meets machine learning, NeurIPS'20](https://arxiv.org/abs/2109.00984)
* [An Efficient 3-Party Framework for Privacy-Preserving Neural Network Inference, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_21)
* [Secure and Verifiable Inference in Deep Neural Networks, ACSAC'20](https://dl.acm.org/doi/abs/10.1145/3427228.3427232)
* [Glyph: Fast and Accurately Training Deep Neural Networks on Encrypted Data, NeurIPS'20](https://arxiv.org/pdf/1911.07101.pdf)
* [CrypTFlow: Secure TensorFlow Inference, S&P'20](https://eprint.iacr.org/2019/1049.pdf)
* [CrypTFlow2: Practical 2-Party Secure Inference, CCS'20](https://arxiv.org/abs/2010.06457)
* [ARIANN: Low-Interaction Privacy-Preserving Deep Learning via Function Secret Sharing, arXiv'20](https://arxiv.org/abs/2006.04593)
* [Practical Privacy-Preserving K-means Clustering, PoPETs'20](https://content.sciendo.com/view/journals/popets/2020/4/article-p414.xml)
* [ABY2.0: Improved Mixed-Protocol Secure Two-Party Computation (Full Version), USENIX Security'21](https://eprint.iacr.org/2020/1225.pdf)
* [SWIFT: Super-fast and Robust Privacy-Preserving Machine Learning, USENIX Security'21](https://arxiv.org/abs/2005.10296)
* [Privacy-preserving Density-based Clustering, AisaCCS'21](https://www.eurecom.fr/publication/6475/download/sec-publi-6475.0.pdf)
* [SIRNN: A Math Library for Secure RNN Inference, S&P'21](https://eprint.iacr.org/2021/459)
* [Let’s Stride Blindfolded in a Forest: Sublinear Multi-Client Decision Trees Evaluation, NDSS'21](https://www.ndss-symposium.org/ndss-paper/lets-stride-blindfolded-in-a-forest-sublinear-multi-client-decision-trees-evaluation/)
* [MUSE: Secure Inference Resilient to Malicious Clients, USENIX Security'21](https://people.eecs.berkeley.edu/~raluca/MUSEcamera.pdf)
* [DeepReDuce: ReLU Reduction for Fast Private Inference, USENIX Security'21](https://arxiv.org/abs/2103.01396)
* [GForce: GPU-Friendly Oblivious and Rapid Neural Network Inference, USENIX Security'21](https://www.usenix.org/conference/usenixsecurity21/presentation/ng)
* [CryptGPU: Fast Privacy-Preserving Machine Learning on the GPU, S&P'21](http://arxiv.org/abs/2104.10949)
* [GALA: Greedy ComputAtion for Linear Algebra in Privacy-Preserved Neural Networks, NDSS'21](https://www.ndss-symposium.org/ndss-paper/gala-greedy-computation-for-linear-algebra-in-privacy-preserved-neural-networks/)
* [Fantastic Four: Honest-Majority Four-Party Secure Computation With Malicious Security, USENIX Security'21](https://www.usenix.org/system/files/sec21fall-dalskov.pdf)
* [When homomorphic encryption marries secret sharing: secure large-scale sparse logistic regression and applications in risk control, KDD'21](https://arxiv.org/abs/2008.08753)
* [Circa: Stochastic ReLUs for Private Deep Learning, NeurIPS'21](https://proceedings.neurips.cc/paper/2021/file/11eba2991cc62daa4a85be5c0cfdae97-Paper.pdf)
* [Mystique: Efficient Conversions for Zero-Knowledge Proofs with Applications to Machine Learning, USENIX Security'21](https://eprint.iacr.org/2021/730)
* [FALCON: Honest-Majority Maliciously Secure Framework for Private Deep Learning, PoPETs'21](https://arxiv.org/abs/2004.02229)
* [SoK: Efficient Privacy-preserving Clustering, PoPETs'21](https://eprint.iacr.org/2021/809)
* [ZEN: Efficient Zero-Knowledge Proofs for Neural Networks, IACR ePrint'21](https://eprint.iacr.org/2021/087)
* [zkCNN: Zero Knowledge Proofs for Convolutional Neural Network Predictions and Accuracy, CCS'21](https://eprint.iacr.org/2021/673)
* [Adam in Private : Secure and Fast Training of Deep Neural Networks with Adaptive Moment Estimation, arXiv'21](https://arxiv.org/abs/2106.02203)
* [Cerebro: A Platform for Multi-Party Cryptographic Collaborative Learning, USENIX Security'21](https://www.usenix.org/conference/usenixsecurity21/presentation/zheng)
* [Tetrad: Actively Secure 4PC for Secure Training and Inference, NDSS'22](https://arxiv.org/abs/2106.02850)
* [SIMC: ML Inference Secure Against Malicious Clients at Semi-Honest Cost, USENIX Security'22](https://www.usenix.org/conference/usenixsecurity22/presentation/chandran)
* [SIMC 2.0: Improved Secure ML Inference Against Malicious Clients, arXiv'22](https://arxiv.org/abs/2207.04637)
* [Cheetah: Lean and Fast Secure Two-Party Deep Neural Network Inference, USENIX Security'22](https://eprint.iacr.org/2022/207)
* [Secure Poisson Regression, USENIX Security'22](https://www.usenix.org/conference/usenixsecurity22/presentation/kelkar)
* [SecFloat: Accurate Floating-Point meets Secure 2-Party Computation, S&P'22](https://eprint.iacr.org/2022/322)
* [MPClan: Protocol Suite for Privacy-Conscious Computations, IACR ePrint'22](https://eprint.iacr.org/2022/675)
* [LLAMA: A Low Latency Math Library for Secure Inference, PoPETs'22](https://eprint.iacr.org/2022/793)
* [Pika: Secure Computation using Function Secret Sharing over Rings, PoPETs'22](https://eprint.iacr.org/2022/826)
* [Piranha: A GPU platform for secure computation, USENIX Security'22](https://www.usenix.org/conference/usenixsecurity22/presentation/watson)
* [Secure Quantized Training for Deep Learning, ICML'22](https://arxiv.org/abs/2107.00501)

## 7.2 Survey

* [机器学习隐私保护研究综述, 软件学报'20](http://www.jos.org.cn/jos/article/abstract/6052)
* [安全多方计算及其在机器学习中的应用, 计算机研究与发展'21](https://crad.ict.ac.cn/CN/10.7544/issn1000-1239.2021.20210626)

## 7.3 Videos
* [Microsoft Research](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn). Videos from SEAL/CKKS talks at Microsoft's Private AI Bootcamp.