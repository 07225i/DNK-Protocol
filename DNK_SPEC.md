
# DNK Protocol Formal Specification (v2.1)

- Algorithms:
  - AES-256 (CBC or GCM)
  - HMAC (SHA3-512, BLAKE2b) chained, each segment HMAC salted by previous
  - Optional BLAKE3 enhancement on DNA checksum
- Nonce replay guard with JSON-based pool and expiry
- Final DNA-style checksum is a base4 encoding of last HMAC
- JSON configuration for flexible crypto settings and expiry windows
