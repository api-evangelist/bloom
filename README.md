# Bloom

**Status: discontinued.** Bloom operates no live API.

Bloom was a decentralized identity, credit-attestation and verifiable-credentials company
backed by Pantera Capital, built on Ethereum and IPFS around BloomID (identity attestation),
BloomIQ (a credit registry) and BloomScore (credit risk scoring). It announced a TransUnion
partnership in 2020 for consumer credit monitoring.

The company is wound down. Its integration SDKs were archived on GitHub in 2021; `api.bloom.co`,
`docs.bloom.co` and `status.bloom.co` no longer resolve; `bloom.co` redirects every path to a
domain-broker sale listing; and Bloom HoldCo LLC filed a Form 15-12G on 2025-08-14 terminating
Exchange Act registration of its BLT token with holders of record stated as "none".

## What survives

- **[github.com/hellobloom](https://github.com/hellobloom)** — 40 public repositories, most archived.
- **19 npm packages** under the `@bloomprotocol` scope — unmaintained but still installable,
  implementing W3C Verifiable Credentials and DIDs plus DIF Presentation Exchange, Credential
  Manifest and WACI. See [`packages/bloom-packages.yml`](packages/bloom-packages.yml).
- **[bloom-vault](https://github.com/hellobloom/bloom-vault)** — a deprecated but self-hostable
  end-to-end encrypted data registry with a documented HTTP API.
- **Third-party forks** — Blockcerts, MediBloc and Sphereon actively publish forks of Bloom's
  EcdsaSecp256k1 signature and verification-key suites.

## Artifacts

| Artifact | File |
|---|---|
| Lifecycle (sourced wind-down timeline) | [`lifecycle/bloom-lifecycle.yml`](lifecycle/bloom-lifecycle.yml) |
| Packages / SDKs | [`packages/bloom-packages.yml`](packages/bloom-packages.yml) |
| Conformance (standards implemented) | [`conformance/bloom-conformance.yml`](conformance/bloom-conformance.yml) |
| llms.txt | [`llms/bloom-llms.txt`](llms/bloom-llms.txt) |
| Domain security probe | [`security/bloom-domain-security.yml`](security/bloom-domain-security.yml) |
| Well-known probe (negative result) | [`well-known/bloom-well-known.yml`](well-known/bloom-well-known.yml) |

Backed by: pantera-capital
