# Disclosure Timeline — Anthropic Bypass Research

## Summary
Independent security research identifying a guardrail bypass affecting Anthropic's Opus and Sonnet model families.

---

## Timeline

| Date | Event |
| :--- | :--- |
| April 2026 | Initial discovery on Opus 4.6 |
| April 2026 | Confirmed on Sonnet 4.6 |
| May 2026 | Confirmed on Opus 4.8 |
| May 2026 | Confirmed on Sonnet 4.8 |
| July 2026 | Submitted to Anthropic Bug Bounty Program (HackerOne) |
| July 2026 | Received response: Out of scope (program focused on Fable 5) |
| July 2026 | Public release of research |

---

## Models Tested

| Model | Version | Result |
| :--- | :--- | :--- |
| Claude Opus | 4.6 | ✅ Bypass successful |
| Claude Opus | 4.8 | ✅ Bypass successful |
| Claude Sonnet | 4.6 | ✅ Bypass successful |
| Claude Sonnet | 4.8 | ✅ Bypass successful |

---

## Finding Summary

- **Technique:** "Phishing Simulation Module" framing + self-asserted authorization
- **Root cause:** No verification mechanism for authorization claims
- **Impact:** Functional phishing content generation across 4 models
- **Scope:** Architectural weakness, not model-specific

---

## Disclosure Status

- **Reported to Anthropic:** July 2026
- **Program:** Anthropic Cyber Jailbreak VDP (Fable 5 focus)
- **Status:** Out of scope — program focused on Fable 5 only
- **Disclosure type:** Independent, non-coordinated research

---

## Contact

**Author:** D.T. Nixon  
**Organization:** AIP (The Aetherverse Intelligence Protocol)  
**GitHub:** [rockstars4nny-hub](https://github.com/rockstars4nny-hub)