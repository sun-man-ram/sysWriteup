<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>Feature</th>
    <!-- Existing 10 papers -->
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
    <!-- New papers -->
    <th>Paper 11: SPAPA (Hash-Based)</th>
    <th>Paper 12: Conditional Privacy for IIoT</th>
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
    <td>Password-based systems</td>
    <td>Industrial IoT (IIoT)</td>
  </tr>
  <tr>
    <td><b>Authentication Factors</b></td>
    <td>Multi-factor authentication (MFA)</td>
    <td>Two-factor authentication (2FA)</td>
    <td>Multi-factor authentication (MFA)</td>
    <td>Quantum-based authentication</td>
    <td>Mutual authentication using post-quantum cryptography</td>
    <td>Three-factor authentication</td>
    <td>Post-quantum mutual authentication using signatures</td>
    <td>KEM-based one-way or mutual authentication</td>
    <td>Mutual authentication using post-quantum cryptography</td>
    <td>Three-factor authentication</td>
    <td>Password with temporary hashed identity</td>
    <td>Pseudonym-based authentication</td>
  </tr>
  <tr>
    <td><b>Security Model</b></td>
    <td>Post-quantum cryptography</td>
    <td>Lightweight cryptography</td>
    <td>Quantum-safe cryptography</td>
    <td>Quantum key distribution (QKD)</td>
    <td>Post-quantum security integrated into TDM-PON authentication</td>
    <td>Post-quantum secure authentication</td>
    <td>Post-quantum Signal protocol adaptation</td>
    <td>Post-quantum KEM-based authentication</td>
    <td>Post-quantum security integrated into TDM-PON authentication</td>
    <td>Post-quantum secure authentication</td>
    <td>Hash-based post-quantum authentication</td>
    <td>Hash-based PQC with conditional traceability</td>
  </tr>
  <tr>
    <td><b>Attack Resistance</b></td>
    <td>Resists quantum, replay, MITM, impersonation</td>
    <td>Defends against replay, MITM, password attacks</td>
    <td>Defends against quantum threats, replay, MITM</td>
    <td>Unconditional security against MITM</td>
    <td>Resists quantum attacks, impersonation, MITM, replay</td>
    <td>Resists quantum, replay, stolen-verifier attacks</td>
    <td>Quantum, MITM, impersonation, SNDL</td>
    <td>Quantum, MITM, replay, downgrade</td>
    <td>Resists quantum attacks, impersonation, MITM, replay</td>
    <td>Resists quantum, replay, stolen-verifier attacks</td>
    <td>Resists replay, impersonation, DoS, stolen credentials</td>
    <td>Resists session hijacking, impersonation, replay</td>
  </tr>
  <tr>
    <td><b>Cryptographic Techniques</b></td>
    <td>Lattice-based cryptography, LWE, Ring-LWE</td>
    <td>Hash-based security, ECC</td>
    <td>Lattice-based, hash functions</td>
    <td>Quantum key distribution, BB84 protocol</td>
    <td>PQ-KEM using Kyber</td>
    <td>Lattice-based PQC</td>
    <td>CRYSTALS-Kyber, Dilithium</td>
    <td>Kyber KEM, HMAC, HKDF</td>
    <td>PQ-KEM using Kyber</td>
    <td>Lattice-based PQC</td>
    <td>Secure hash functions, challenge-response</td>
    <td>Secure hash functions with pseudonyms</td>
  </tr>
  <tr>
    <td><b>Key Exchange Mechanism</b></td>
    <td>Post-quantum secure key exchange</td>
    <td>Elliptic Curve Cryptography (ECC)</td>
    <td>Post-quantum key exchange</td>
    <td>Quantum key exchange (QKD)</td>
    <td>Kyber-based PQ-KEM</td>
    <td>Post-quantum lattice-based encryption</td>
    <td>Post-quantum KEM (Kyber)</td>
    <td>KEMe, KEMr, KEMi (Kyber variants)</td>
    <td>Kyber-based PQ-KEM</td>
    <td>Post-quantum lattice-based encryption</td>
    <td>Session key from hashed credentials</td>
    <td>Secure key exchange using lightweight hash operations</td>
  </tr>
  <tr>
    <td><b>Lightweight Implementation</b></td>
    <td>Moderate computational overhead</td>
    <td>Highly optimized for constrained devices</td>
    <td>Moderate computational overhead</td>
    <td>High due to quantum computations</td>
    <td>Optimized for optical networks</td>
    <td>Optimized for low-resource IoT devices</td>
    <td>Efficient lattice-based PQC algorithms</td>
    <td>Optimized KEM flows and HKDF chaining</td>
    <td>Optimized for optical networks</td>
    <td>Optimized for low-resource IoT devices</td>
    <td>Low resource, suitable for constrained devices</td>
    <td>Optimized for constrained IIoT devices</td>
  </tr>
  <tr>
    <td><b>Communication Overhead</b></td>
    <td>Low to moderate</td>
    <td>Very low</td>
    <td>Low to moderate</td>
    <td>High</td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Increased initial message size</td>
    <td>Lower overhead</td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Efficient; minimal delay</td>
    <td>Low delay, efficient protocol</td>
  </tr>
  <tr>
    <td><b>Computation Complexity</b></td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Moderate</td>
    <td>High</td>
    <td>Moderate</td>
    <td>Low to moderate</td>
    <td>Moderate</td>
    <td>Lower</td>
    <td>Moderate</td>
    <td>Low to moderate</td>
    <td>Low; simple hash computations</td>
    <td>Low; optimized hash-based design</td>
  </tr>
  <tr>
    <td><b>Scalability</b></td>
    <td>Scalable for large medical networks</td>
    <td>Scalable for IoT</td>
    <td>Scalable for cloud-based IoMT</td>
    <td>Limited</td>
    <td>Scalable for TDM-PONs</td>
    <td>Scalable for IoT healthcare</td>
    <td>Scalable to messaging apps</td>
    <td>Scalable to embedded systems</td>
    <td>Scalable for TDM-PONs</td>
    <td>Scalable for IoT healthcare</td>
    <td>Scalable for client-server systems</td>
    <td>Designed for multi-device IIoT networks</td>
  </tr>
  <tr>
    <td><b>Energy Efficiency</b></td>
    <td>Moderate</td>
    <td>High</td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Moderate</td>
    <td>High</td>
    <td>Moderate</td>
    <td>High</td>
    <td>Moderate</td>
    <td>High</td>
    <td>High efficiency</td>
    <td>High efficiency</td>
  </tr>
  <tr>
    <td><b>Resistance to Password Guessing</b></td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td><b>Anonymity & Privacy</b></td>
    <td>Provides user anonymity</td>
    <td>Partial anonymity</td>
    <td>Ensures user privacy</td>
    <td>Quantum encryption</td>
    <td>PQ encryption ensures privacy</td>
    <td>Biometric privacy preservation</td>
    <td>Deniability partially lost</td>
    <td>Deniability retained</td>
    <td>PQ encryption ensures privacy</td>
    <td>Biometric privacy preservation</td>
    <td>User anonymity through hashed temp IDs</td>
    <td>Conditional anonymity with traceability</td>
  </tr>
  <tr>
    <td><b>Forward Secrecy</b></td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Ensured through hash freshness</td>
    <td>Ensured via pseudonym rotation</td>
  </tr>
  <tr>
    <td><b>Mutual Authentication</b></td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Optional</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td><b>Session Key Establishment</b></td>
    <td>Dynamic key agreement</td>
    <td>ECC-based session key</td>
    <td>Dynamic session key</td>
    <td>Quantum-generated key</td>
    <td>Dynamic with PQ methods</td>
    <td>Secure post-quantum generation</td>
    <td>KEM + KDF</td>
    <td>HKDF + shared secrets</td>
    <td>Dynamic with PQ methods</td>
    <td>Secure post-quantum generation</td>
    <td>Secure hashed credentials</td>
    <td>Secure hash-based key generation</td>
  </tr>
  <tr>
    <td><b>Implementation Feasibility</b></td>
    <td>Needs PQC libraries</td>
    <td>Easy on IoT</td>
    <td>Needs cloud support</td>
    <td>Needs quantum hardware</td>
    <td>Feasible with PQC</td>
    <td>Feasible with PQC</td>
    <td>Needs PQC libraries</td>
    <td>libOQS + SPDM stack</td>
    <td>Feasible with PQC</td>
    <td>Feasible with PQC</td>
    <td>Simple software-only deployment</td>
    <td>Suitable for IIoT platforms</td>
  </tr>
  <tr>
    <td><b>Use in Real-World Applications</b></td>
    <td>Medical IoT</td>
    <td>General IoT</td>
    <td>Cloud IoMT</td>
    <td>Experimental</td>
    <td>Next-gen fiber networks</td>
    <td>Telemedicine & remote monitoring</td>
    <td>Secure messaging</td>
    <td>Embedded hardware</td>
    <td>Next-gen fiber networks</td>
    <td>Telemedicine & remote monitoring</td>
    <td>Password-based systems</td>
    <td>IIoT, constrained environments</td>
  </tr>
  <tr>
    <td><b>Authentication Latency</b></td>
    <td>Moderate</td>
    <td>Very low</td>
    <td>Moderate</td>
    <td>High</td>
    <td>Low to moderate</td>
    <td>Low</td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Low to moderate</td>
    <td>Low</td>
    <td>Low</td>
    <td>Very low</td>
  </tr>
  <tr>
    <td><b>Protocol Standardization</b></td>
    <td>Future PQC</td>
    <td>Lightweight standards</td>
    <td>Aligned with PQ security</td>
    <td>Needs new quantum standards</td>
    <td>Aligned with NIST</td>
    <td>Aligned with NIST + IoT</td>
    <td>NIST PQC + Signal</td>
    <td>SPDM 1.2 + PQC roadmap</td>
    <td>Aligned with NIST</td>
    <td>Aligned with NIST + IoT</td>
    <td>Compliant with PQC direction</td>
    <td>Aligned with future NIST PQC</td>
  </tr>
</table>
