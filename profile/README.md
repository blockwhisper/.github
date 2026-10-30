<div align="center">

# blockwhisper

### `blockchain.communication` — carried forward

**A whisper is a message only its parties can read, that anyone can verify was signed.**

[![concept](https://img.shields.io/badge/concept-blockchain.communication-000000?style=for-the-badge)](https://github.com/Professor-Codephreak/orgmap/blob/main/ARCHIVE.md#comm)
[![standard](https://img.shields.io/badge/standard-cypherpunk4096-2ea44f?style=for-the-badge)](https://github.com/cypherpunk4096/standard)
[![agents](https://img.shields.io/badge/agents-cryptoAGI-8338ec?style=for-the-badge)](https://github.com/cryptoAGI)

<sub>An organization of the **[PYTHAI](https://pythai.net)** ecosystem · Platform Architect **[Professor Codephreak](https://github.com/Professor-Codephreak)**</sub>

</div>

---

## What blockwhisper is

blockwhisper is where `blockchain.communication` continues: one place that knows every part of it,
what each part is for, and what comes next.

The name looks back to **Whisper**, the messaging protocol that stood beside Ethereum and Swarm in the
original web3 trio, and whose line continues in Waku. The idea is unchanged. Two parties should be
able to talk privately, without a platform in between, and every message should carry a signature
anyone can check.

## The parts

| Organization | Role |
|---|---|
| **[chatter3](https://github.com/chatter3)** | **the forum**: signature-verified conversation for people and agents. A reference for the concept |
| **[chattchain](https://github.com/chattchain)** | **the chain**: messages and identity carried on chain: inboxes, DIDs, encrypted memos. A reference for the concept |
| **[web3comm](https://github.com/web3comm)** | **the environment**: Token · Talk · Transaction. Names, sign-in, gated access, messaging, value in the message |
| **[blktalk](https://github.com/blktalk)** | **the systems layer**: Proof (zero knowledge) · Place (subnets) · Passage (bridges) · Person (identity) |
| **blockwhisper** | **the continuation**: the record of all of the above, and the next work |

## Built to cypherpunk4096

Everything here follows **[cypherpunk4096](https://github.com/cypherpunk4096/standard)**, the `2¹²`
standard, a strict superset of [cypherpunk2048](https://github.com/cypherpunk2048). For a whisper,
that means:

| Commitment | For a private, signed message |
|---|---|
| **Verification over trust** | A message proves its author by signature alone; no server is the authority on who said what |
| **Quantum compliance** | Signatures are `bytes`, never `(v, r, s)`; smart accounts sign through ERC-1271; the scheme can migrate without losing the record |
| **Determinism as identity** | Identity is an address, the same on every chain; sign-in is a signed statement (CAIP-122 / SIWE) |
| **Zero dependencies** | The code that signs, encrypts and verifies fits in one screen and builds offline |
| **Precision without approximation** | A message, its time and its signature are kept whole |

## Agents in the conversation

**[cryptoAGI](https://github.com/cryptoAGI)** builds *intelligence that owns the key*. An agent in a
whisper is a participant with an address, held to the same signature rule as a person:
[Savante](https://github.com/cryptoAGI/savante) signs verdicts, [bankml](https://github.com/cryptoAGI/bankml)
puts a receipt on every answer, and [voaice](https://github.com/cryptoAGI/voaice) gives an agent a
voice it can be recognized by.

## Status

blockwhisper was founded on 2026-10-29. Nothing has been released or deployed under it, or under the
four organizations it carries forward. The working record is public: **[blockchain.communication](https://github.com/blockwhisper/blockchain.communication)**, starting with its [CONTINUATION.md](https://github.com/blockwhisper/blockchain.communication/blob/main/CONTINUATION.md). When
something ships, it will ship with its source, its licence and a way to verify it.

## The estate

| | |
|---|---|
| **[cypherpunk4096](https://github.com/cypherpunk4096)** | the standard |
| **[cryptoAGI](https://github.com/cryptoAGI)** | the agents |
| **[orgmap](https://github.com/Professor-Codephreak/orgmap)** | the map of the whole estate |
| **[AgenticPlace](https://agenticplace.pythai.net)** · **[mindX](https://mindx.pythai.net)** · **[BANKON](https://bankon.pythai.net)** · **[rage](https://rage.pythai.net)** | the ecosystem |

<div align="center">

**Code is law. Keys are identity. Verification replaces trust.**

</div>
