# Awesome Privacy Computing

# 1 Secure Multiparty Computation (SMPC)

### 1.1 Primitive

#### 1.1.1 Oblivious Transfer (OT)
- [Precomputing Oblivious Transfer, CRYPTO'95](https://link.springer.com/content/pdf/10.1007%2F3-540-44750-4_8.pdf)
- [Efficient Oblivious Transfer Protocols, SODA'01](https://dl.acm.org/doi/10.5555/365411.365502)
- IKNP03: [Extending Oblivious Transfers Efficiently, CRYPTO'03](http://link.springer.com/10.1007/978-3-540-45146-4_9)
- ALSZ13: [More Efficient Oblivious Transfer and Extensions for Faster Secure Computation, CCS'13](https://eprint.iacr.org/2013/552.pdf), [slide](https://www.cs.cornell.edu/~asharov/slides/ALSZ13.pdf)
- KK13: [Improved OT Extension for Transferring Short Secrets, CRYPTO'13](https://eprint.iacr.org/2013/491.pdf)
- KOS15: [Actively Secure OT Extension with Optimal Overhead, CRYPTO'15](https://eprint.iacr.org/2015/546.pdf)
- [MASCOT: Faster Malicious Arithmetic Secure Computation with Oblivious Transfer, CCS'16](https://eprint.iacr.org/2016/505.pdf)
- [Fast Actively Secure OT Extension for Short Secrets, NDSS'17](http://arxiv.org/abs/1911.08834), [slide](https://www.ndss-symposium.org/wp-content/uploads/2017/09/ndss2017_04B-1-suresh-slides.pdf), [video](https://youtu.be/urV3ljX-DqQ)
- [Efficient Pseudorandom Correlation Generators: Silent OT Extension and More, CRYPTO'19](https://eprint.iacr.org/2019/448.pdf)
- [Efficient two-round OT extension and silent non-interactive secure computation, CCS'19](https://eprint.iacr.org/2019/1159.pdf)
- [Ferret: Fast Extension for Correlated OT with Small Communication, CCS'20](https://eprint.iacr.org/2020/924.pdf)
- [Silver: Silent VOLE and Oblivious Transfer from Hardness of Decoding Structured LDPC Codes, CRYPTO'21](https://eprint.iacr.org/2021/1150.pdf)

#### 1.1.2 Garbled Circuit

- [Protocols for Secure Computations (Extended Abstract), STOC'82]( https://crysp.uwaterloo.ca/courses/pet/F11/cache/www.cs.wisc.edu/areas/sec/yao1982-ocr.pdf)
- [Improved Garbled Circuit: Free XOR Gates and Applications, ICALP'08](http://www.cs.toronto.edu/~vlad/papers/XOR_ICALP08.pdf)
- [FairplayMP – A System for Secure Multi-Party Computation, CCS'08](https://www.cs.huji.ac.il/~noam/FairplayMP.pdf)
- [Secure Two-Party Computation Is Practical, ASIACRYPT'09](https://eprint.iacr.org/2009/314.pdf)
- [Foundations of Garbled Circuits, CCS'12](https://eprint.iacr.org/2012/265.pdf)
- [FleXOR: Flexible Garbling for XOR Gates That Beats Free-XOR, CRYPTO'14](https://eprint.iacr.org/2014/460.pdf)
- [Two Halves Make a Whole: Reducing Data Transfer in Garbled Circuits using Half Gates, EUROCRYPT'15](https://eprint.iacr.org/2014/756.pdf)
- MRZ15: [Fast and Secure Three-party Computation: The Garbled Circuit Approach, CCS'15](https://eprint.iacr.org/2015/931.pdf)
- [Three Halves Make a Whole? Beating the Half-Gates Lower Bound for Garbled Circuits, CRYPTO'21](https://eprint.iacr.org/2021/749.pdf)

#### 1.1.3  Arithmetic/Boolean Circuit

- [GMW: How to play ANY mental game, STOC'87](https://www.researchgate.net/publication/234778924_How_to_play_ANY_mental_game/link/0deec5232112523fc5000000/download)
- [Multiparty Computation from Somewhat Homomorphic Encryption](https://eprint.iacr.org/2011/535.pdf)
- [Practical Covertly Secure MPC for Dishonest Majority Or: Breaking the SPDZ Limits](https://eprint.iacr.org/2012/642.pdf) 
- [SPDZ2k: Efficient MPC mod 2k for Dishonest Majority](https://eprint.iacr.org/2018/482.pdf)

#### 1.1.5 A/B/Y Shares Conversion

- [ABY – A Framework for Effificient Mixed-Protocol Secure Two-Party Computation, NDSS'15](https://encrypto.de/papers/DSZ15.pdf)
- [ABY3 : A Mixed Protocol Framework for Machine Learning, CCS'18](https://eprint.iacr.org/2018/403.pdf)
- [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2019/1315)
- [MP-SPDZ: A versatile framework for multi-party computation, CCS'20](https://eprint.iacr.org/2020/521.pdf)
- [ABY2.0: Improved Mixed-Protocol Secure Two-Party Computation, USENIX Security'21](https://eprint.iacr.org/2020/1225.pdf)
- [MOTION – A Framework for Mixed-Protocol Multi-Party Computation, TOPS'22](https://eprint.iacr.org/2020/1137)
- [Tetrad: Actively Secure 4PC for Secure Training and Inference, NDSS'22](https://arxiv.org/abs/2106.02850)

#### 1.1.6 PSI

- [Efficient Batched Oblivious PRF with Applications to Private Set Intersection, CCS'16](https://eprint.iacr.org/2016/799.pdf), [code: BaRK-OPRF](https://github.com/osu-crypto/BaRK-OPRF)
- [Actively Secure 1-out-of-N OT Extension with Application to Private Set Intersection, CT-RSA'17](https://eprint.iacr.org/2016/933.pdf)
- [SpOT-Light: Lightweight Private Set Intersection from Sparse OT Extension, CRYPTO'19](https://eprint.iacr.org/2019/634.pdf)
- [PSI from PaXoS: Fast, Malicious Private Set Intersection, EUROCRYPT'20](https://eprint.iacr.org/2020/193.pdf)
- [VOLE-PSI: Fast OPRF and Circuit-PSI from Vector-OLE, EUROCRYPT'21](https://eprint.iacr.org/2021/266.pdf)
- [LibPSI](https://github.com/osu-crypto/libPSI)
- [PSI](https://github.com/encryptogroup/PSI), [2014/447](https://eprint.iacr.org/2014/447).

#### 1.1.7 Multiparty ECDSA signing

- [Blockchain-Crypto-MPC](https://github.com/unbound-tech/blockchain-crypto-mpc), [CCS'18](https://eprint.iacr.org/2018/987)
- [MPECDSA](https://gitlab.com/neucrypt/mpecdsa), [S&P'19](https://eprint.iacr.org/2019/523.pdf)



## 1.2 Survey

- Yehuda Lindell. [Secure Multiparty Computation (MPC)](https://eprint.iacr.org/2020/300.pdf)
- Yehuda Lindell. [How to Simulate It - A Tutorial on the Simulation Proof Technique](https://eprint.iacr.org/2016/046.pdf)
- Manoj Prabhakaran and Amit Sahai (Eds.) [Secure Multi-Party Computation](http://ebooks.iospress.com/volume/secure-multi-party-computation)

## 1.3 Books

- [A Pragmatic Introduction to Secure Multi-Party Computation](https://securecomputation.org/)
- [Applications of Secure Multiparty Computation](http://ebooks.iospress.nl/volume/applications-of-secure-multiparty-computation)
- [Efficient Secure Two-Party Protocols](https://www.springer.com/us/book/9783642143021)
- [Secure Multiparty Computation and Secret Sharing](http://www.cambridge.org/dk/academic/subjects/computer-science/cryptography-cryptology-and-coding/secure-multiparty-computation-and-secret-sharing?format=HB)

- [Foundations of Cryptography Vol. 2 ](http://www.wisdom.weizmann.ac.il/~oded/foc-vol2.html)
- [Engineering Secure Two-Party Computation Protocols ](https://www.sites.google.com/site/thomaschneider/publications/engineeringsfebook)


## 1.4 Courses

- [Cryptographic Computing Course](http://orlandi.dk/crycom)
- [FHE-MPC Advanced Grad Course](https://homes.esat.kuleuven.be/~nsmart/FHE-MPC/)
- [Secure Computation](http://drona.csa.iisc.ernet.in/~arpita/SecureComputation15.html)
- [Secure Multi-Party Computation at Scale](https://piazza.com/bu/fall2017/cs591v1/home)
- [The 1st BIU Winter School on Secure Computation and Efficiency](https://cyber.biu.ac.il/event/the-1st-biu-winter-school/)
- [The 5th BIU Winter School on Advances in Practical Multiparty Computation](https://cyber.biu.ac.il/event/the-5th-biu-winter-school/)
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

## FHE Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.
- <a name="SEAL">[Microsoft SEAL](https://github.com/microsoft/SEAL) - C++ FHE library implementing BFV and CKKS schemes.</a>
- <a name="HEAAN">[HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic.
- <a name="HElib">[HElib](https://github.com/HomEnc/HElib) - BGV scheme with bootstrapping and the Approximate Number CKKS scheme.
- <a name="lattigo">[lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
- <a name="PALISADE">[PALISADE](https://palisade-crypto.org/software-library) - lattice encryption library.
- <a name="tfhe">[tfhe](https://github.com/tfhe/tfhe) - Faster fully HE: Bootstrapping in less than 0.1 seconds.</a>
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816).
- [concrete](https://github.com/zama-ai/concrete) - Rust FHE library that implements Zama's variant of TFHE.
- [Cupcake](https://github.com/facebookresearch/Cupcake) - Facebook's Rust library for the (additive version of the) Fan-Vercauteren scheme.

## FHE Applications
- [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE and deep / federated learning.
	- [KotlinSyft](https://github.com/OpenMined/KotlinSyft) - Kotlin library for the Android part of the OpenMined's open-source ecosystem.
	- [PySyft](https://github.com/OpenMined/PySyft) - Python library for the server/IoT part of the OpenMined's open-source ecosystem.
	- [SwiftSyft](https://github.com/OpenMined/SwiftSyft) - Swift library for the iOS part of the OpenMined's open-source ecosystem.
	- [syft.js](https://github.com/OpenMined/syft.js) - JavaScript library for the web part of the OpenMined's open-source ecosystem.
- [Rosetta](https://github.com/LatticeX-Foundation/Rosetta) - A privacy-preserving framework based on TensorFlow.
- [tf-encrypted](https://github.com/tf-encrypted/tf-encrypted) - Bridge between TensorFlow and the [Microsoft SEAL](#SEAL) library.

## FHE Papers

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
- [Efficient Homomorphic Comparison Methods with Optimal Complexity, ASIACRYPT'2020](https://link.springer.com/10.1007/978-3-030-64834-3_8)
- [PEGASUS: Bridging polynomial and non-polynomial evaluations in homomorphic encryption, S&P'21](https://ieeexplore.ieee.org/document/9519408/)
- [General Bootstrapping Approach for RLWE-based Homomorphic Encryption, ePrint'21](https://eprint.iacr.org/2021/691)
- [On the Security of Homomorphic Encryption on Approximate Numbers, EUROCRYPT'21](https://link.springer.com/10.1007/978-3-030-77870-5_23)
- [Efficient Bootstrapping for Approximate Homomorphic Encryption with Non-sparse Keys, EUROCRYPT'21](https://link.springer.com/10.1007/978-3-030-77870-5_21)
- [Efficient Homomorphic Conversion Between (Ring) LWE Ciphertexts, ACNS'21](https://link.springer.com/chapter/10.1007/978-3-030-78372-3_18)
  
# 5 Differential Privacy (DP)

# 6 Zero-Knowledge Proof (ZKP)

# 7 Privacy-Preserving Machine Learning (PPML)

* [Machine Learning Classification over Encrypted Data, NDSS'14](https://eprint.iacr.org/2014/331.pdf)
* [Oblivious Multi-Party Machine Learning on Trusted Processors, USENIX SECURITY'16](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/ohrimenko)
* [Prio: Private, Robust, and Scalable Computation of Aggregate Statistics, NSDI'17](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/corrigan-gibbs)
* [SecureML: A System for Scalable Privacy-Preserving Machine Learning, S&P'17](https://eprint.iacr.org/2017/396)
* [MiniONN: Oblivious Neural Network Predictions via MiniONN Transformations, CCS'17](https://acmccs.github.io/papers/p619-liuA.pdf)
* [Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications, AsiaCCS'17](https://eprint.iacr.org/2017/1164)
* [DeepSecure: Scalable Provably-Secure Deep Learning, DAC'17](https://arxiv.org/abs/1705.08963)
* [Secure Computation for Machine Learning With SPDZ, NIPS'18](https://arxiv.org/abs/1901.00329)
* [ABY3:a Mixed protocol Framework for Machine Learning, CCS'18](https://eprint.iacr.org/2018/403.pdf)
* [SecureNN: Efficient and Private Neural Network Training, PETS'18](https://eprint.iacr.org/2018/442.pdf)
* [Gazelle: A Low Latency Framework for Secure Neural Network Inference, USENIX SECURITY'18](https://arxiv.org/abs/1801.05507)
* [CHET: an optimizing compiler for fully-homomorphic neural-network inferencing, PLDI'19](https://dl.acm.org/citation.cfm?id=3314628)
* [New Primitives for Actively-Secure MPC over Rings with Applications to Private Machine Learning, S&P'19](https://eprint.iacr.org/2019/599.pdf)
* [Helen: Maliciously Secure Coopetitive Learning for Linear Models, S&P'19](https://ieeexplore.ieee.org/abstract/document/8835215)
* [Efficient multi-key homomorphic encryption with packed ciphertexts with application to oblivious neural network inference. CCS'19](https://dl.acm.org/citation.cfm?id=3363207)
* [XONN: XNOR-based Oblivious Deep Neural Network Inference, USENIX Security'19](https://www.usenix.org/conference/usenixsecurity19/presentation/riazi)
* [QUOTIENT: two-party secure neural network training and prediction, CCS'19](https://dl.acm.org/citation.cfm?id=3339819)
* [Secure Evaluation of Quantized Neural Networks, PETS'20](https://content.sciendo.com/view/journals/popets/2020/4/article-p355.xml)
* [ASTRA: High Throughput 3PC over Rings with Application to Secure Prediction, CCSW'19](https://eprint.iacr.org/2019/429)
* [SoK: Modular and Efficient Private Decision Tree Evaluation, PETS'19](https://eprint.iacr.org/2018/1099.pdf)
* [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2019/1315)
* [BLAZE: Blazing Fast Privacy-Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2020/042)
* [FLASH: Fast and Robust Framework for Privacy-preserving Machine Learning, PETS'20](https://eprint.iacr.org/2019/1365)
* [Delphi: A Cryptographic Inference Service for Neural Networks, USENIX SECURITY'20](https://eprint.iacr.org/2020/050)
* [FALCON: Honest-Majority Maliciously Secure Framework for Private Deep Learning, PETS'21](https://arxiv.org/abs/2004.02229)
* [MP2ML: A Mixed-Protocol Machine Learning Framework for Private Inference, ARES'20](https://dl.acm.org/doi/abs/10.1145/3407023.3407045)
* [SANNS: Scaling Up Secure Approximate k-Nearest Neighbors Search, USENIX Security'20](https://www.usenix.org/conference/usenixsecurity20/presentation/chen-hao)
* [PySyft: A Generic Framework for Privacy Preserving Deep Learning](https://arxiv.org/abs/1811.04017)
* [Private Deep Learning in TensorFlow Using Secure Computation](https://arxiv.org/abs/1810.08130)
* [CryptoDL: Deep Neural Networks over Encrypted Data](https://arxiv.org/abs/1711.05189)
* [CryptoNets: Applying Neural Networks to Encrypted Data with High Throughput and Accuracy](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/04/CryptonetsTechReport.pdf)
* [CrypTFlow: Secure TensorFlow Inference](https://eprint.iacr.org/2019/1049.pdf)
* [CrypTFlow2: Practical 2-Party Secure Inference, CCS'20](https://arxiv.org/abs/2010.06457)
* [ARIANN: Low-Interaction Privacy-Preserving Deep Learning via Function Secret Sharing](https://arxiv.org/abs/2006.04593)
* [Practical Privacy-Preserving K-means Clustering, PETS'20](https://content.sciendo.com/view/journals/popets/2020/4/article-p414.xml)
* [ABY2.0: Improved Mixed-Protocol Secure Two-Party Computation (Full Version), USENIX Security'21](https://eprint.iacr.org/2020/1225.pdf)
* [SWIFT: Super-fast and Robust Privacy-Preserving Machine Learning](https://arxiv.org/abs/2005.10296)
* [An Efficient 3-Party Framework for Privacy-Preserving Neural Network Inference, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_21)
* [Secure and Verifiable Inference in Deep Neural Networks, ACSAC'20](https://dl.acm.org/doi/abs/10.1145/3427228.3427232)
* [Privacy-preserving Density-based Clustering, AisaCCS'21](https://www.eurecom.fr/publication/6475/download/sec-publi-6475.0.pdf)
* [SIRNN: A Math Library for Secure RNN Inference, S&P'21](https://eprint.iacr.org/2021/459)
* [Let’s Stride Blindfolded in a Forest: Sublinear Multi-Client Decision Trees Evaluation, NDSS'21](https://www.ndss-symposium.org/ndss-paper/lets-stride-blindfolded-in-a-forest-sublinear-multi-client-decision-trees-evaluation/)
* [MUSE: Secure Inference Resilient to Malicious Clients](https://people.eecs.berkeley.edu/~raluca/MUSEcamera.pdf)
* [DeepReDuce: ReLU Reduction for Fast Private Inference, USENIX Security'21](https://arxiv.org/abs/2103.01396)
* [Garbled Neural Networks are Practical](https://eprint.iacr.org/2019/338.pdf)
* [GForce : GPU-Friendly Oblivious and Rapid Neural Network Inference, USENIX Security'21](https://www.usenix.org/conference/usenixsecurity21/presentation/ng)
* [CryptGPU: Fast Privacy-Preserving Machine Learning on the GPU, S&P'21](http://arxiv.org/abs/2104.10949)
* [GALA : Greedy ComputAtion for Linear Algebra in Privacy-Preserved Neural Networks, NDSS'21](https://www.ndss-symposium.org/ndss-paper/gala-greedy-computation-for-linear-algebra-in-privacy-preserved-neural-networks/)
* [Fantastic Four: Honest-Majority Four-Party Secure Computation With Malicious Security, USENIX Security'21](https://www.usenix.org/system/files/sec21fall-dalskov.pdf)
* [When homomorphic encryption marries secret sharing: secure large-scale sparse logistic regression and applications in risk control, KDD'21](https://arxiv.org/abs/2008.08753)
* [Microsoft Research](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn). Videos from SEAL/CKKS talks at Microsoft's Private AI Bootcamp.

