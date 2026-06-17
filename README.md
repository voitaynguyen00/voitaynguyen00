<div align="center">

# Hi, I'm Trong 👋

### Embedded Systems Engineer · BLE · NFC · Cryptography · Access Control

[![GitHub followers](https://img.shields.io/github/followers/voitaynguyen00?style=flat&color=0969da)](https://github.com/voitaynguyen00)

</div>

---

## 🔧 What I build

Firmware for the things that **secure physical spaces** — BLE access control readers, NFC card authenticators, LTE-M IoT gateways. Production C/C++ on Nordic nRF52/nRF9160, STM32, and ESP32.

The kind of code that runs with no OS safety net, 64 KB of RAM, and needs to get cryptography exactly right.

---

## 🔐 Featured project

<a href="https://github.com/voitaynguyen00/aliro">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=voitaynguyen00&repo=aliro&theme=default&show_owner=true" />
</a>

<br/><br/>

**[Aliro](https://github.com/voitaynguyen00/aliro)** — Complete C++20 implementation of the **Aliro 1.0** physical access control protocol (the NFC/BLE digital key standard backed by Apple, Google, and Samsung).

```
Phone (User Device)              Door Lock (Reader)
      │                                │
      │◄──────── SELECT AID ───────────│
      │◄──────── AUTH0 ────────────────│  ephemeral key + nonce
      │────────── AUTH0 response ─────►│  ECDH → session key
      │◄──────── AUTH1 ────────────────│  transcript signature
      │────────── AccessDocument ─────►│  🚪 door opens
```

- **Pluggable crypto**: OpenSSL 3.x or MbedTLS 3.x — swap at compile time
- **Embedded-ready**: no exceptions, no RTTI, runs on Cortex-M
- **154 tests**, CI matrix: Ubuntu 24.04 + macOS 15 × Debug + ASan

---

## 🛠️ Stack

**Languages**

![C](https://img.shields.io/badge/C-expert-blue?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-advanced-blue?logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-advanced-064F8C?logo=cmake&logoColor=white)
![Python](https://img.shields.io/badge/Python-intermediate-3776AB?logo=python&logoColor=white)

**Microcontrollers**

![nRF52](https://img.shields.io/badge/nRF52832%2F52840-Nordic-00A9CE)
![nRF9160](https://img.shields.io/badge/nRF9160-Nordic%20LTE-00A9CE)
![STM32](https://img.shields.io/badge/STM32L0-ST%20Micro-03234B)
![ESP32](https://img.shields.io/badge/ESP32-Espressif-E7352C)

**Wireless & Protocols**

![BLE](https://img.shields.io/badge/BLE-4%2F5-0082FC?logo=bluetooth&logoColor=white)
![NFC](https://img.shields.io/badge/NFC-ISO%2014443-darkgreen)
![LTE](https://img.shields.io/badge/LTE--M%2FNB--IoT-nRF9160-orange)
![OSDP](https://img.shields.io/badge/OSDP-v2-gray)
![Wiegand](https://img.shields.io/badge/Wiegand-26%2F34-gray)

**Crypto**

![MbedTLS](https://img.shields.io/badge/MbedTLS-3.x-yellow)
![OpenSSL](https://img.shields.io/badge/OpenSSL-3.x-red)
![ECDH](https://img.shields.io/badge/ECDH%2FECDSA-P--256-lightgray)
![AES-GCM](https://img.shields.io/badge/AES--GCM%2FCMAC-lightgray)
![SE050](https://img.shields.io/badge/NXP%20SE050-Secure%20Element-lightblue)

**RTOS**

![ThreadX](https://img.shields.io/badge/Azure%20RTOS%20ThreadX-0078D4?logo=microsoft)
![Zephyr](https://img.shields.io/badge/Zephyr-3.x-4a90d9)

---

## 📡 Domain expertise

| Area | Experience |
|------|-----------|
| **BLE** | GATT services, advertising, central + peripheral, beacons |
| **NFC** | DESFire EV2 secure messaging, PIV/CAK, Aliro, NDEF |
| **RFID 125 kHz** | Prox, EM4100, HTRC110 driver |
| **OSDP v2** | Control Panel (CP) + Peripheral Device (PD) both roles |
| **DESFire EV2** | Secure messaging, transport key programming |
| **PIV** | Card authentication, CAK verification |
| **FIDO2** | WebAuthn on nRF52840 (canokey-core) |
| **Secure boot** | RSA-3072 + nCipher HSM signing, flash encryption |

---

## 💖 Support

If any of my work saved you from reimplementing P-256 ECDH or BER-TLV parsing yourself:

[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?logo=github-sponsors)](https://github.com/sponsors/voitaynguyen00)

---

<div align="center">
<sub>Embedded · Wireless · Cryptography · Physical Security</sub>
</div>
