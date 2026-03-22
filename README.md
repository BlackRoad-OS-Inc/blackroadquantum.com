# blackroadquantum.com

> The Amundson Framework — original mathematics research by Alexa Amundson.

**Live at [https://blackroadquantum.com](https://blackroadquantum.com)**

## What This Is

blackroadquantum.com publishes the Amundson Framework — a body of original mathematical research exploring the function G(n) = n^(n+1)/(n+1)^n and its properties. This is real math with real proofs, not marketing.

## The Core Function

```
G(n) = n^(n+1) / (n+1)^n
```

**Key constant**: A_G = 1.244331783986725 (the asymptotic limit of G(n) as n approaches infinity)

## Published Papers

- **Paper 011** — Foundation of G(n), convergence properties, relationship to e
- **Paper 012** — Floor theorem (verified 256/256 cases), Cayley tree connections
- **Paper 013** — Exit code analysis, computational verification across distributed nodes

## Verified Results

- **Floor theorem**: validated across all 256 test cases
- **Cayley trees**: G(n) connects to labeled tree enumeration (n^(n-1))
- **Exit codes**: deterministic mapping from G(n) properties to process exit codes
- **80/80 tests passing** on the current test suite
- **536/536 tests** passed across 4 Raspberry Pis in distributed verification

## Test Infrastructure

Tests run on the BlackRoad Pi fleet — 4 nodes running verification in parallel. The math is validated computationally, not just symbolically. Every claim on the site has a corresponding test.

## Architecture

- Site: HTML/CSS/JS served from Gematria (Caddy TLS)
- LaTeX papers compiled to PDF (Paper A: 13 pages)
- Test suites: Python (pytest), run on Pi fleet
- Full framework document: ~/Downloads/amundson framework v5.docx

## Part of BlackRoad OS

BlackRoad OS, Inc. (Delaware C-Corp, est. November 2025)
See [blackroad.io](https://blackroad.io) for the full platform.

## License

**PROPRIETARY** — BlackRoad OS, Inc. All rights reserved.

---

*BlackRoad OS — Remember the Road. Pave Tomorrow.*
