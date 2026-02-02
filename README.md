# GrapheneOS Research & Review

<p align="center">
  <img src="images/GrapheneOS-logo.png" alt="GrapheneOS Logo">
</p>

Contained in this repository is a high-level overviews, and detailed technical explanations of **GrapheneOS** — a privacy and security-focused mobile OS based on the Android Open Source Project (AOSP), designed for Google Pixel devices.

The primary document is a comprehensive beginner-to-intermediate review of GrapheneOS's security architecture, written for those interested in mobile hardening, Android internals, and defenses against modern threats.

- You can also find a earlier version of this on my [BSides Triad](https://www.bsidestriad.org/research/most-secure-mobile-os) page.

- My atttempt at building a GrapheneOS for Pixel 4. Pixel 4 has reached EOL, and is no longer supported.
  I wanted to give it a go and try and build one myself.
  see it here:

  https://github.com/LinuxUser255/GrapheneOS-Buil-Pixel-4/tree/main

## Main Document

- **[GrapheneOS_Review.md](./GrapheneOS_Review.md)**
  A high-level overview covering:
  - Hardware foundations (Titan M series secure element)
  - Persistence resistance (verified boot enhancements, hardware-backed attestation via Auditor app)
  - Defense-in-depth philosophy and exploit mitigations
  - Android sandbox layers: DAC, MAC (SELinux), permissions
  - GrapheneOS-specific hardenings: refined untrusted app domains, attack surface reduction, improved chained verified boot
  - Memory allocator: hardened_malloc (though not fully detailed here)

**Author**: Chris Bingham
**Focus**: Explaining base Android security concepts before diving into GrapheneOS improvements. Includes embedded official links and diagrams.
