# Awesome Privacy Computing

# 1 Secure Multiparty Computation (SMPC)

### 1.1 Primitive

#### 1.1.1 Oblivious Transfer (OT)

- More Efficient Oblivious Transfer and Extensions for Faster Secure Computation. [paper](https://eprint.iacr.org/2013/552.pdf), [slide](https://www.cs.cornell.edu/~asharov/slides/ALSZ13.pdf). 

#### 1.1.2 Garbled Circuit

1. [Protocols for Secure Computations (Extended Abstract)]( https://crysp.uwaterloo.ca/courses/pet/F11/cache/www.cs.wisc.edu/areas/sec/yao1982-ocr.pdf)
2. [Improved Garbled Circuit: Free XOR Gates and Applications](http://www.cs.toronto.edu/~vlad/papers/XOR_ICALP08.pdf)
3. [FairplayMP – A System for Secure Multi-Party Computation](https://www.cs.huji.ac.il/~noam/FairplayMP.pdf)
4. [Two Halves Make a Whole Reducing Data Transfer in Garbled Circuits using Half Gates](https://eprint.iacr.org/2014/756.pdf)
5. [Fast and Secure Three-party Computation: The Garbled Circuit Approach](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/43888.pdf)

#### 1.1.3 Arithmetic Circuit

1. [Multiparty Computation from Somewhat Homomorphic Encryption](https://eprint.iacr.org/2011/535.pdf)
2. [Practical Covertly Secure MPC for Dishonest Majority Or: Breaking the SPDZ Limits](https://eprint.iacr.org/2012/642.pdf) 
3. [SPDZ2k: Efficient MPC mod 2k for Dishonest Majority](https://eprint.iacr.org/2018/482.pdf)

#### 1.1.4 Boolean Circuit

1. [How to play any mental game or a completeness theorem for protocols with honest majority (PDF) How to play ANY mental game](https://www.researchgate.net/publication/234778924_How_to_play_ANY_mental_game/link/0deec5232112523fc5000000/download)

#### 1.1.5 Protocol

1. [ABY – A Framework for Effificient Mixed-Protocol Secure Two-Party Computation, NDSS'15](https://encrypto.de/papers/DSZ15.pdf)
2. [ABY3 : A Mixed Protocol Framework for Machine Learning, CCS'18](https://eprint.iacr.org/2018/403.pdf)
3. [BLAZE: Blazing Fast Privacy-Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2020/042)
4. [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2019/1315)
5. [MOTION – A Framework for Mixed-Protocol Multi-Party Computation](https://eprint.iacr.org/2020/1137)

#### 1.1.6 PSI

- [BaRK-OPRF](https://github.com/osu-crypto/BaRK-OPRF), [2016/799](https://eprint.iacr.org/2016/799).
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

- [Foundations of Cryptography Vol. 2 ](http://www.wisdom.weizmann.ac.il/~oded/foc-vol2.html).
- [Engineering Secure Two-Party Computation Protocols ](https://www.sites.google.com/site/thomaschneider/publications/engineeringsfebook).


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
