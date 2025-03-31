<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>Feature</th>
    <th>Paper 1</th>
    <th>Paper 2</th>
    <th>Paper 3</th>
    <th>Paper 4</th>
    <th>Paper 5</th>
    <th>Paper 6</th>
    <th>Paper 7</th>
    <th>Paper 8</th>
    <th>Paper 9</th>
    <th>Paper 10</th>
    <th>Paper 11</th>
    <th>Paper 12</th>
    <th>Paper 13</th>
    <th>Paper 14</th>
    <th>Paper 15</th>
    <th>Paper 16</th>
  </tr>
  
  <!-- Domain -->
  <tr>
    <td><b>Domain</b></td>
    <td>IoMT</td>
    <td>General IoT</td>
    <td>Cloud-assisted Medical IoT</td>
    <td>Quantum authentication</td>
    <td>Telecommunication Networks</td>
    <td>IoT Healthcare</td>
    <td>Secure messaging</td>
    <td>Device-level security</td>
    <td>Telecommunication Networks</td>
    <td>IoT Healthcare</td>
    <td>Password-based systems</td>
    <td>Industrial IoT</td>
    <td>OTP Authentication</td>
    <td>Quantum Password Auth</td>
    <td>Public Cloud</td>
    <td>V2X Communication</td>
  </tr>

  <!-- Authentication Factors -->
  <tr>
    <td><b>Authentication Factors</b></td>
    <td>MFA</td>
    <td>2FA</td>
    <td>MFA</td>
    <td>Quantum-based</td>
    <td>Mutual auth with PQC</td>
    <td>Three-factor</td>
    <td>PQ mutual auth</td>
    <td>KEM-based</td>
    <td>Mutual auth with PQC</td>
    <td>Three-factor</td>
    <td>Password + temp ID</td>
    <td>Pseudonym-based</td>
    <td>2FA with OTP</td>
    <td>Quantum copy-protection</td>
    <td>Lattice-based mutual auth</td>
    <td>Pseudonym-based (BLISS+NTRU)</td>
  </tr>

  <!-- Security Model -->
  <tr>
    <td><b>Security Model</b></td>
    <td>Post-quantum</td>
    <td>Lightweight</td>
    <td>Quantum-safe</td>
    <td>QKD</td>
    <td>PQ in TDM-PONs</td>
    <td>PQ secure</td>
    <td>PQ Signal adaptation</td>
    <td>PQ KEM-based</td>
    <td>PQ in TDM-PONs</td>
    <td>PQ secure</td>
    <td>Hash-based PQ</td>
    <td>Hash-based with traceability</td>
    <td>Quantum-resistant</td>
    <td>Honest-Malicious</td>
    <td>RLWE, ROR model</td>
    <td>BLISS+NTRU, IND-CCA2</td>
  </tr>

  <!-- Attack Resistance -->
  <tr>
    <td><b>Attack Resistance</b></td>
    <td>Quantum, MITM, replay</td>
    <td>Replay, MITM</td>
    <td>Quantum, MITM</td>
    <td>Unconditional MITM</td>
    <td>Quantum, MITM, replay</td>
    <td>Quantum, replay</td>
    <td>Quantum, MITM</td>
    <td>Quantum, MITM</td>
    <td>Quantum, MITM, replay</td>
    <td>Quantum, replay</td>
    <td>Replay, DoS</td>
    <td>Session hijacking</td>
    <td>Quantum-resistant</td>
    <td>Quantum brute-force</td>
    <td>Quantum, MITM, replay</td>
    <td>Quantum, MITM, replay</td>
  </tr>

  <!-- Cryptographic Techniques -->
  <tr>
    <td><b>Cryptographic Techniques</b></td>
    <td>LWE, Ring-LWE</td>
    <td>Hash, ECC</td>
    <td>Lattice-based</td>
    <td>BB84 protocol</td>
    <td>Kyber</td>
    <td>Lattice PQC</td>
    <td>Kyber, Dilithium</td>
    <td>Kyber, HMAC</td>
    <td>Kyber</td>
    <td>Lattice PQC</td>
    <td>Secure hash</td>
    <td>Lightweight hash</td>
    <td>NTRU, SPHINCS+</td>
    <td>Steane code</td>
    <td>RLWE</td>
    <td>BLISS, NTRU Prime</td>
  </tr>

  <!-- Key Exchange Mechanism -->
  <tr>
    <td><b>Key Exchange Mechanism</b></td>
    <td>PQ key exchange</td>
    <td>ECC</td>
    <td>PQ key exchange</td>
    <td>QKD</td>
    <td>Kyber-based</td>
    <td>Lattice-based</td>
    <td>PQ KEM</td>
    <td>HKDF</td>
    <td>Kyber-based</td>
    <td>Lattice-based</td>
    <td>Hashed credentials</td>
    <td>Lightweight hash</td>
    <td>NTRU</td>
    <td>FrodoKEM</td>
    <td>RLWE-based</td>
    <td>NTRU Prime KEM</td>
  </tr>

  <!-- Lightweight Implementation -->
  <tr>
    <td><b>Lightweight Implementation</b></td>
    <td>Moderate</td>
    <td>Highly optimized</td>
    <td>Moderate</td>
    <td>High (quantum)</td>
    <td>Optical networks</td>
    <td>Low-resource IoT</td>
    <td>Efficient PQ</td>
    <td>Optimized KEM</td>
    <td>Optical networks</td>
    <td>Low-resource IoT</td>
    <td>Constrained devices</td>
    <td>Constrained IIoT</td>
    <td>PQC efficiency</td>
    <td>Quantum circuits</td>
    <td>Cloud-optimized</td>
    <td>V2X-optimized</td>
  </tr>

  <!-- Communication Overhead -->
  <tr>
    <td><b>Communication Overhead</b></td>
    <td>Low-moderate</td>
    <td>Very low</td>
    <td>Low-moderate</td>
    <td>High</td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Increased initial</td>
    <td>Lower</td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Minimal delay</td>
    <td>Efficient</td>
    <td>NTRU vs RSA/AES</td>
    <td>Quantum noise</td>
    <td>8736 bits total</td>
    <td>Moderate</td>
  </tr>

  <!-- Computation Complexity -->
  <tr>
    <td><b>Computation Complexity</b></td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Moderate</td>
    <td>High</td>
    <td>Moderate</td>
    <td>Low-moderate</td>
    <td>Moderate</td>
    <td>Lower</td>
    <td>Moderate</td>
    <td>Low-moderate</td>
    <td>Low</td>
    <td>Low</td>
    <td>PQC benchmarks</td>
    <td>Noise mitigation</td>
    <td>0.0039ms</td>
    <td>Moderate</td>
  </tr>

  <!-- Scalability -->
  <tr>
    <td><b>Scalability</b></td>
    <td>Large networks</td>
    <td>IoT</td>
    <td>Cloud IoMT</td>
    <td>Limited</td>
    <td>TDM-PONs</td>
    <td>IoT healthcare</td>
    <td>Messaging apps</td>
    <td>Embedded</td>
    <td>TDM-PONs</td>
    <td>IoT healthcare</td>
    <td>Client-server</td>
    <td>Multi-device</td>
    <td>1000 users</td>
    <td>IBM quantum</td>
    <td>Cloud-scale</td>
    <td>V2X networks</td>
  </tr>

  <!-- Energy Efficiency -->
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
    <td>High</td>
    <td>High</td>
    <td>Not specified</td>
    <td>Not specified</td>
    <td>Cloud-optimized</td>
    <td>Moderate</td>
  </tr>

  <!-- Resistance to Password Guessing -->
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
    <td>PQC hashing</td>
    <td>Copy-protection</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>

  <!-- Anonymity & Privacy -->
  <tr>
    <td><b>Anonymity & Privacy</b></td>
    <td>User anonymity</td>
    <td>Partial</td>
    <td>User privacy</td>
    <td>Quantum encryption</td>
    <td>PQ encryption</td>
    <td>Biometric privacy</td>
    <td>Partial deniability</td>
    <td>Deniability</td>
    <td>PQ encryption</td>
    <td>Biometric privacy</td>
    <td>Hashed temp IDs</td>
    <td>Conditional</td>
    <td>OTP secrecy</td>
    <td>Limited</td>
    <td>Identity protection</td>
    <td>Pseudonym privacy</td>
  </tr>

  <!-- Forward Secrecy -->
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
    <td>Hash freshness</td>
    <td>Pseudonym rotation</td>
    <td>Not specified</td>
    <td>Not specified</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>

  <!-- Mutual Authentication -->
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
    <td>Server-to-user</td>
    <td>Server-to-quantum</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>

  <!-- Session Key Establishment -->
  <tr>
    <td><b>Session Key Establishment</b></td>
    <td>Dynamic key</td>
    <td>ECC-based</td>
    <td>Dynamic</td>
    <td>Quantum key</td>
    <td>Dynamic PQ</td>
    <td>PQ generation</td>
    <td>KEM + KDF</td>
    <td>HKDF</td>
    <td>Dynamic PQ</td>
    <td>PQ generation</td>
    <td>Hashed creds</td>
    <td>Hash-based</td>
    <td>Not specified</td>
    <td>Quantum SSL</td>
    <td>RLWE-based</td>
    <td>NTRU Prime</td>
  </tr>

  <!-- Implementation Feasibility -->
  <tr>
    <td><b>Implementation Feasibility</b></td>
    <td>PQC libraries</td>
    <td>Easy IoT</td>
    <td>Cloud support</td>
    <td>Quantum hardware</td>
    <td>Feasible PQC</td>
    <td>Feasible PQC</td>
    <td>PQC libraries</td>
    <td>libOQS</td>
    <td>Feasible PQC</td>
    <td>Feasible PQC</td>
    <td>Software-only</td>
    <td>IIoT platforms</td>
    <td>PQC in OTP</td>
    <td>Qiskit tools</td>
    <td>Cloud-ready</td>
    <td>V2X feasible</td>
  </tr>

  <!-- Use in Real-World Applications -->
  <tr>
    <td><b>Use in Real-World Applications</b></td>
    <td>Medical IoT</td>
    <td>General IoT</td>
    <td>Cloud IoMT</td>
    <td>Experimental</td>
    <td>Fiber networks</td>
    <td>Telemedicine</td>
    <td>Secure messaging</td>
    <td>Embedded</td>
    <td>Fiber networks</td>
    <td>Telemedicine</td>
    <td>Password systems</td>
    <td>IIoT</td>
    <td>Banking MFA</td>
    <td>PQ password</td>
    <td>Public cloud</td>
    <td>V2X systems</td>
  </tr>

  <!-- Authentication Latency -->
  <tr>
    <td><b>Authentication Latency</b></td>
    <td>Moderate</td>
    <td>Very low</td>
    <td>Moderate</td>
    <td>High</td>
    <td>Low-moderate</td>
    <td>Low</td>
    <td>Moderate</td>
    <td>Low</td>
    <td>Low-moderate</td>
    <td>Low</td>
    <td>Low</td>
    <td>Very low</td>
    <td>NTRU faster</td>
    <td>Quantum noise</td>
    <td>Optimized</td>
    <td>Moderate</td>
  </tr>

  <!-- Protocol Standardization -->
  <tr>
    <td><b>Protocol Standardization</b></td>
    <td>Future PQC</td>
    <td>Lightweight</td>
    <td>PQ security</td>
    <td>New quantum</td>
    <td>NIST</td>
    <td>NIST + IoT</td>
    <td>NIST + Signal</td>
    <td>SPDM 1.2</td>
    <td>NIST</td>
    <td>NIST + IoT</td>
    <td>PQC direction</td>
    <td>Future NIST</td>
    <td>NIST PQC</td>
    <td>IBM Quantum</td>
    <td>NIST candidates</td>
    <td>IEEE 1609</td>
  </tr>
</table>
