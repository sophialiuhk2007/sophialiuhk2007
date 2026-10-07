# Hi, I'm Sophia 👋

I study **Computer Science, Mathematics and Statistics at Harvard**. I'm interested in
**machine learning for biology**, **cryptography** and **ML theory**.

## Research

- **Klein Lab** and **Sompolinsky Lab**, Harvard
- **Learning cell-adhesion energies with autodiff (Summer 2026).** I use JAX to differentiate through
  cell-sorting simulations and learn the adhesion energy matrix that produces a target multicellular
  pattern. [`autodiff-adhesion-patterning`](https://github.com/sophialiuhk2007/autodiff-adhesion-patterning)
  is a limited public preview of this work.

Most of my research code is in private lab repositories or tied to manuscripts in preparation, so my
contribution graph shows only part of my work. I'm happy to share more on request.

## Post-quantum cryptography: Quip Network

I implement and optimize **SHRINCS** hash-based post-quantum signatures (WOTS-C, FORS-C) for on-chain
verification. The work so far covers:

- Solidity verifiers for the stateful and stateless signing paths, with gas measurement and optimization
- A Rust signer and verifier that generates the test vectors
- WASM bindings
- Tests and documentation

| Repository | My work |
|---|---|
| [hashsigs-solidity](https://github.com/QuipNetwork/hashsigs-solidity) | ~50 commits: SHRINCS verifier, FORS-C, gas measurements and optimizations, tests. [My commits →](https://github.com/QuipNetwork/hashsigs-solidity/commits/shrincs-forsc/?author=sophialiuhk2007) |
| [hashsigs-rs](https://github.com/QuipNetwork/hashsigs-rs) | SHRINCS signer, verifier and vector generation, WASM bindings (shipped in `v0.1.0-rc1`). [My commits →](https://github.com/QuipNetwork/hashsigs-rs/commits/shrincs-main/?author=sophialiuhk2007) |
| shrincs-solidity *(private)* | Original SHRINCS prototype: WOTS-C, stateful and stateless paths, gas harnesses |

This work lives on the SHRINCS release branches rather than `main`, so it doesn't show on my
contribution graph. The links above go to the commit history.

## Selected projects

| Project | Description |
|---|---|
| [**VeriTrust Issuer Portal**](https://github.com/sophialiuhk2007/credo-project-v2) | Verifiable-credentials platform built on Credo: template-driven SD-JWT issuance (OpenID4VCI), selective disclosure, OpenID4VP verification and Apple Wallet passes |
| [**VeriTrust Wallet**](https://github.com/sophialiuhk2007/AwesomeProject) | React Native holder app for VeriTrust, on the App Store |
| [**Harvard A-grade cap & enrollment**](https://github.com/sophialiuhk2007/hodp-grade-cap-enrollment) | Harvard Open Data Project analysis of whether the "20% + 4" A-grade cap changed course enrollment |
| [**MBTA station closures map**](https://github.com/sophialiuhk2007/HODP) | HODP interactive map of where MBTA service failures occur |
| [**Academic VC**](https://github.com/sophialiuhk2007/academic-vc) | My first verifiable-credentials system, for academic diplomas and club memberships (2023) |

**Languages and tools:** Python · JAX · NumPy/pandas · Rust · Solidity · TypeScript · React Native · Node.js
