Post-Quantum Key Encapsulation with Kyber
This project provides a Python implementation of a Post-Quantum Cryptography (PQC) Key Encapsulation Mechanism (KEM) using the ML-KEM (Kyber) algorithm.

What is Lattice-based Cryptography?
Lattice-based cryptography is a type of asymmetric cryptography based on the hardness of specific geometric problems in multi-dimensional structures called lattices.

Unlike RSA or Elliptic Curve Cryptography (ECC), which rely on the difficulty of integer factorization or discrete logarithms, lattices are believed to be resistant to attacks by both classical and quantum computers.

The primary security foundation for Kyber is the Learning With Errors (LWE) problem over modules (Module-LWE). It involves finding a secret vector in a high-dimensional space where "noise" (error) has been added to the coordinates, making it statistically impossible to solve without the private key.

Why Kyber?
Kyber (now standardized by NIST as ML-KEM) was selected for its high efficiency and relatively small key sizes. In our implementation, we use Kyber768, which provides a security level approximately equivalent to AES-192, balancing performance and robust quantum resistance.

References and Further Reading
To understand the mathematics and the standardization process behind Kyber, please refer to:

NIST FIPS 203 (Draft): The official standard for Module-Lattice-Based Key-Encapsulation Mechanism.

pq-crystals.org: The official website of the CRYSTALS (Cryptographic Suite for Algebraic Lattices) team, creators of Kyber.

Open Quantum Safe (OQS): The library used in this script, which aims to support the transition to quantum-resistant cryptography.
