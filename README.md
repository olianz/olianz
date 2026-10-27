<div align="center">

# olianz

### Open Source · Software Engineering · Verifiable Computing

I'm a Saudi-based open-source contributor exploring **zero-knowledge proof systems**, **reliable verification**, and **defensive software testing**.

I use AI development tools extensively, and I believe technical contributions should be judged by **clear evidence, reproducible tests, and maintainer review**.

[![GitHub](https://img.shields.io/badge/GitHub-olianz-181717?logo=github)](https://github.com/olianz)
[![zkFOL](https://img.shields.io/badge/zkFOL-Contributions-2ea44f)](https://github.com/zkFOL/zkfol/pulls?q=is%3Apr+author%3Aolianz)
[![Verified CI](https://img.shields.io/badge/zkFOL_CI-179_Tests_Passed-208636?logo=githubactions)](https://github.com/olianz/zkfol/actions/runs/40248923293)

</div>

---

## Featured work

### [zkFOL — Proof verification input hardening (PR #15)](https://github.com/zkFOL/zkfol/pull/15)

Improved defensive validation at the Elixir–Rust verification boundary:

- Reject inconsistent public-column dimensions, out-of-range references, and malformed constraint programs.
- Handle malformed proof decoding as a controlled error.
- Preserve existing verification behavior and regression coverage.
- **Validation:** [175 Elixir tests + 4 Rust tests passed](https://github.com/olianz/zkfol/actions/runs/40248923293).

**Status:** Submitted for maintainer review. This is a robustness improvement, not a claim of an exploitable vulnerability.

## Other contributions

| Contribution | Evidence |
| --- | --- |
| [zkFOL — limb tampering, overflow, and padding regression tests (PR #6)](https://github.com/zkFOL/zkfol/pull/6) | Maintainer [incorporated the work upstream](https://github.com/zkFOL/zkfol/commit/ba97ecd7cbd995bb8f78018c540ad9b5d7802288); PR closed without direct merge |
| [zkFOL — standalone verifier corrupted-proof test (PR #8)](https://github.com/zkFOL/zkfol/pull/8) | [CI passed](https://github.com/olianz/zkfol/actions/runs/39581654876); under review |
| [zkFOL — refusal mapping short-circuit test (PR #13)](https://github.com/zkFOL/zkfol/pull/13) | Submitted; verification and maintainer review pending |
| [zkFOL — negative column-offset validation (PR #14)](https://github.com/zkFOL/zkfol/pull/14) | Submitted; verification and maintainer review pending |

## How I work

1. Study the existing implementation and its expected behavior.
2. Make focused changes with a clear reason and scope.
3. Add meaningful regression tests and run CI where available.
4. Document what was actually tested and what still needs review.
5. Respect project conventions, security policies, and maintainer feedback.

**AI transparency:** AI tools assist significantly with my coding and research. I do not present unverified AI output as a tested result.

## Areas of interest

- Zero-knowledge proofs and verifier correctness
- Input validation and defensive regression tests
- Rust–Elixir integration
- Test automation and reproducible CI
- Open-source collaboration and well-defined funded issues

---

<div align="center">

**Open to well-scoped contributions and collaborations.**

[GitHub activity](https://github.com/olianz?tab=overview) · [zkFOL pull requests](https://github.com/zkFOL/zkfol/pulls?q=is%3Apr+author%3Aolianz)

<sub>For live PR and merge status, follow the linked GitHub records.</sub>

</div>
