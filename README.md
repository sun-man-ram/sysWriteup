<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>Feature</th>
    <th>Paper 1: IoMT (Post-Quantum)</th>
    <th>Paper 2: Lightweight 2FA</th>
    <th>Paper 3: Quantum-Safe MFA</th>
    <th>Paper 4: Quantum Authentication</th>
    <th>Paper 5: Post-Quantum for TDM-PONs</th>
    <th>Paper 6: PQ IoT Healthcare</th>
    <th>Paper 7: Post-Quantum E2EE Protocol</th>
    <th>Paper 8: KEM-SPDM Secure Session</th>
    <th>Paper 9: Post-Quantum for TDM-PONs</th>
    <th>Paper 10: PQ IoT Healthcare</th>
  </tr>
  <tr>
    <td><b>Domain</b></td>
    <td>Internet of Medical Things (IoMT)</td>
    <td>General IoT and user authentication</td>
    <td>Cloud-assisted Medical IoT</td>
    <td>Quantum authentication systems</td>
    <td>Telecommunication Networks (TDM-PONs)</td>
    <td>IoT-Based Healthcare Systems</td>
    <td>Secure messaging and communication protocols</td>
    <td>Device-level secure session establishment</td>
    <td>Telecommunication Networks (TDM-PONs)</td>
    <td>IoT-Based Healthcare Systems</td>
  </tr>
  <tr>
    <td><b>Authentication Factors</b></td>
    <td>Multi-factor authentication (MFA)</td>
    <td>Two-factor authentication (2FA)</td>
    <td>Multi-factor authentication (MFA)</td>
    <td>Quantum-based authentication</td>
    <td>Mutual authentication using post-quantum cryptography</td>
    <td>Three-factor authentication (biometric, password, and PQ cryptography)</td>
    <td>Post-quantum mutual authentication using signatures</td>
    <td>KEM-based one-way or mutual authentication</td>
    <td>Mutual authentication using post-quantum cryptography</td>
    <td>Three-factor authentication (biometric, password, and PQ cryptography)</td>
  </tr>
  <tr>
    <td><b>Security Model</b></td>
    <td>Post-quantum cryptography</td>
    <td>Lightweight cryptography</td>
    <td>Quantum-safe cryptography</td>
    <td>Quantum key distribution (QKD)</td>
    <td>Post-quantum security integrated into TDM-PON authentication</td>
    <td>Post-quantum secure authentication with IoT healthcare compliance</td>
    <td>Post-quantum Signal protocol adaptation</td>
    <td>Post-quantum KEM-based authentication</td>
    <td>Post-quantum security integrated into TDM-PON authentication</td>
    <td>Post-quantum secure authentication with IoT healthcare compliance</td>
  </tr>
  <tr>
    <td><b>Attack Resistance</b></td>
    <td>Resists quantum, replay, MITM, impersonation</td>
    <td>Defends against replay, MITM, password attacks</td>
    <td>Defends against quantum threats, replay, MITM</td>
    <td>Unconditional security against MITM</td>
    <td>Resists quantum attacks, impersonation, MITM, replay</td>
    <td>Resists quantum attacks, replay attacks, stolen-verifier attacks</td>
    <td>Quantum, MITM, impersonation, SNDL</td>
    <td>Quantum, MITM, replay, downgrade</td>
    <td>Resists quantum attacks, impersonation, MITM, replay</td>
    <td>Resists quantum attacks, replay attacks, stolen-verifier attacks</td>
  </tr>
  <tr>
    <td><b>Cryptographic Techniques</b></td>
    <td>Lattice-based cryptography, LWE, Ring-LWE</td>
    <td>Hash-based security, ECC</td>
    <td>Lattice-based, hash functions</td>
    <td>Quantum key distribution, BB84 protocol</td>
    <td>Post-Quantum Key Encapsulation Mechanism (PQ-KEM) using Kyber</td>
    <td>Post-Quantum Cryptography (PQC) with lattice-based encryption</td>
    <td>CRYSTALS-Kyber, Dilithium</td>
    <td>Kyber KEM, HMAC, HKDF</td>
    <td>Post-Quantum Key Encapsulation Mechanism (PQ-KEM) using Kyber</td>
    <td>Post-Quantum Cryptography (PQC) with lattice-based encryption</td>
  </tr>
  <tr>
    <td><b>Key Exchange Mechanism</b></td>
    <td>Post-quantum secure key exchange</td>
    <td>Elliptic Curve Cryptography (ECC)</td>
    <td>Post-quantum key exchange</td>
    <td>Quantum key exchange (QKD)</td>
    <td>Post-quantum key exchange using Kyber</td>
    <td>Secure key establishment via post-quantum lattice-based encryption</td>
    <td>Post-quantum KEM (Kyber)</td>
    <td>KEMe, KEMr, KEMi (all Kyber variants)</td>
    <td>Post-quantum key exchange using Kyber</td>
    <td>Secure key establishment via post-quantum lattice-based encryption</td>
  </tr>
  <tr>
    <td><b>Lightweight Implementation</b></td>
    <td>Moderate computational overhead</td>
    <td>Highly optimized for constrained devices</td>
    <td>Moderate computational overhead</td>
    <td>High due to quantum computations</td>
    <td>Optimized for optical network authentication</td>
    <td>Optimized for low-resource IoT devices</td>
    <td>Efficient lattice-based PQC algorithms</td>
    <td>Optimized KEM flows and HKDF chaining</td>
    <td>Optimized for optical network authentication</td>
    <td>Optimized for low-resource IoT devices</td>
  </tr>
  <tr>
    <td><b>Communication Overhead</b></td>
    <td>Low to moderate</td>
    <td>Very low</td>
    <td>Low to moderate</td>
    <td>High due to quantum communication</td>
    <td>Moderate (depends on PQ-KEM efficiency)</td>
    <td>Low (optimized for IoT environments)</td>
    <td>Increased initial message size (signatures, public keys)</td>
    <td>Lower overhead by eliminating signatures</td>
    <td>Moderate (depends on PQ-KEM efficiency)</td>
    <td>Low (optimized for IoT environments)</td>
  </tr>
  <tr>
    <td><b>Computation Complexity</b></td>
    <td>Moderate due to post-quantum methods</td>
    <td>Low due to ECC and hash-based techniques</td>
    <td>Moderate</td>
    <td>High (Quantum processing)</td>
    <td>Moderate (PQ-KEM operations)</td>
    <td>Low to moderate (lightweight PQ cryptographic techniques)</td>
    <td>Moderate due to signatures and KEMs</td>
    <td>Lower due to KEM-only usage</td>
    <td>Moderate (PQ-KEM operations)</td>
    <td>Low to moderate (lightweight PQ cryptographic techniques)</td>
  </tr>
  <tr>
    <td><b>Scalability</b></td>
    <td>Scalable for large medical networks</td>
    <td>Scalable for IoT and mobile applications</td>
    <td>Scalable for cloud-based IoMT</td>
    <td>Limited scalability</td>
    <td>Scalable for TDM-PON networks</td>
    <td>Scalable for various IoT-based healthcare applications</td>
    <td>Scalable to messaging apps (e.g., Signal, WhatsApp)</td>
    <td>Scalable to IoT and embedded systems</td>
    <td>Scalable for TDM-PON networks</td>
    <td>Scalable for various IoT-based healthcare applications</td>
  </tr>
  <tr>
    <td><b>Energy Efficiency</b></td>
    <td>Moderate</td>
    <td>High energy efficiency</td>
    <td>Moderate</td>
    <td>Low due to quantum operations</td>
    <td>Moderate (depends on network implementation)</td>
    <td>High (optimized for IoT power constraints)</td>
    <td>Moderate (PQ signature cost)</td>
    <td>High (no signatures required)</td>
    <td>Moderate (depends on network implementation)</td>
    <td>High (optimized for IoT power constraints)</td>
  </tr>
  <tr>
    <td><b>Resistance to Password Guessing</b></td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes (PQ-KEM prevents brute-force attacks)</td>
    <td>Yes (multi-factor authentication enhances resistance)</td>
    <td>Yes (key-based encryption)</td>
    <td>Yes (randomized key encapsulation)</td>
    <td>Yes (PQ-KEM prevents brute-force attacks)</td>
    <td>Yes (multi-factor authentication enhances resistance)</td>
  </tr>
  <tr>
    <td><b>Anonymity & Privacy</b></td>
    <td>Provides user anonymity and unlinkability</td>
    <td>Partially supports anonymity</td>
    <td>Ensures user privacy</td>
    <td>Quantum encryption ensures privacy</td>
    <td>Ensures privacy through post-quantum encryption</td>
    <td>Strong privacy preservation with biometric security</td>
    <td>Some deniability lost due to signatures</td>
    <td>Deniability retained using ephemeral KEM</td>
    <td>Ensures privacy through post-quantum encryption</td>
    <td>Strong privacy preservation with biometric security</td>
  </tr>
  <tr>
    <td><b>Forward Secrecy</b></td>
    <td>Ensured through post-quantum techniques</td>
    <td>Ensured through ECC-based key agreement</td>
    <td>Ensured</td>
    <td>Ensured via quantum no-cloning theorem</td>
    <td>Yes (via Kyber-based PQ-KEM session keys)</td>
    <td>Yes (via lattice-based PQC)</td>
    <td>Yes (via one-time keys and double ratchet)</td>
    <td>Yes (via ephemeral KEMe)</td>
    <td>Yes (via Kyber-based PQ-KEM session keys)</td>
    <td>Yes (via lattice-based PQC)</td>
  </tr>
  <tr>
    <td><b>Mutual Authentication</b></td>
    <td>Yes, between user and IoMT devices</td>
    <td>Yes, between user and authentication server</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes (between Optical Network Units and OLTs)</td>
    <td>Yes (between healthcare IoT devices and authentication servers)</td>
    <td>Yes (via signatures)</td>
    <td>Optional (based on KEMr and KEMi)</td>
    <td>Yes (between Optical Network Units and OLTs)</td>
    <td>Yes (between healthcare IoT devices and authentication servers)</td>
  </tr>
  <tr>
    <td><b>Session Key Establishment</b></td>
    <td>Dynamic key agreement</td>
    <td>ECC-based session key generation</td>
    <td>Dynamic session key agreement</td>
    <td>Quantum-generated session keys</td>
    <td>Dynamic session keys using post-quantum cryptographic methods</td>
    <td>Secure session key generation through post-quantum techniques</td>
    <td>Concatenated KEM keys + KDF</td>
    <td>HKDF from shared secrets (ssr, sse, ssi)</td>
    <td>Dynamic session keys using post-quantum cryptographic methods</td>
    <td>Secure session key generation through post-quantum techniques</td>
  </tr>
  <tr>
    <td><b>Implementation Feasibility</b></td>
    <td>Requires quantum-resistant cryptographic libraries</td>
    <td>Easily deployable on IoT devices</td>
    <td>Requires cloud-based support</td>
    <td>Requires quantum communication devices</td>
    <td>Feasible for TDM-PONs with PQC integration</td>
    <td>Feasible for IoT healthcare applications with PQC adoption</td>
    <td>Requires integration with post-quantum libraries (e.g., Kyber/Dilithium)</td>
    <td>Prototype available with libOQS + SPDM stack</td>
    <td>Feasible for TDM-PONs with PQC integration</td>
    <td>Feasible for IoT healthcare applications with PQC adoption</td>
  </tr>
  <tr>
    <td><b>Use in Real-World Applications</b></td>
    <td>Suitable for medical IoT</td>
    <td>Suitable for general IoT authentication</td>
    <td>Best suited for cloud-based IoMT</td>
    <td>Experimental stage, not widely used</td>
    <td>Suited for next-generation secure fiber-optic networks</td>
    <td>Applicable to telemedicine, remote patient monitoring, and IoT security</td>
    <td>End-to-end secure messaging (Signal alternative)</td>
    <td>Embedded devices, SPDM-secured hardware</td>
    <td>Suited for next-generation secure fiber-optic networks</td>
    <td>Applicable to telemedicine, remote patient monitoring, and IoT security</td>
  </tr>
  <tr>
    <td><b>Authentication Latency</b></td>
    <td>Moderate delay due to post-quantum processing</td>
    <td>Very low latency</td>
    <td>Moderate latency</td>
    <td>High due to quantum state preparation</td>
    <td>Low to moderate (optimized for high-speed networks)</td>
    <td>Low (lightweight cryptographic operations reduce delays)</td>
    <td>Moderate due to digital signatures</td>
    <td>Low (KEM-only based handshakes)</td>
    <td>Low to moderate (optimized for high-speed networks)</td>
    <td>Low (lightweight cryptographic operations reduce delays)</td>
  </tr>
  <tr>
    <td><b>Protocol Standardization</b></td>
    <td>Future adoption in post-quantum cryptography</td>
    <td>Aligns with lightweight security standards</td>
    <td>Aligned with post-quantum security</td>
    <td>Requires new quantum cryptography standards</td>
    <td>Aligned with NIST PQC standards</td>
    <td>Aligned with NIST PQC and IoT security standards</td>
    <td>Follows NIST PQC, adapts Signal</td>
    <td>Aligned with SPDM 1.2 extensions and PQC roadmap</td>
    <td>Aligned with NIST PQC standards</td>
    <td>Aligned with NIST PQC and IoT security standards</td>
  </tr>
</table>
