
# DNK Protocol v2.1 (DNA-style Sealed Round-Trip with Enhancements)

This is an updated version of the DNK Protocol by Dovgopol Anton Aleksandrovich (Ukraine),
which implements DNA-style chained sealed round-trip mutual verification.

## 🚀 What's new in v2.1:
- Added JSON-based nonce pool for more robust anti-replay protection.
- Strengthened DNA checksum using double HMAC and optional BLAKE3.
- Introduced formal spec file (DNK_SPEC.md) describing the protocol structure.
- Added JSON config (dnk_config.json) for easy tuning by banks or IoT systems.

This architecture is designed for:
- Portable AI memory synchronization across devices
- Banking escrow multi-step verification
- IoT command integrity with anti-tamper chains

## 📜 Ownership
Author: Dovgopol Anton Aleksandrovich (Ukraine)
Email: gpt4officials@gmail.com
Phone: +380957052757
