# Daniil Ankushin

**Ethereum core developer @ [Nethermind](https://nethermind.io)** — execution clients, EVM, consensus-critical code. [Protocol Guild](https://protocol-guild.readthedocs.io) member.

## What I work on

**Native Account Abstraction (Frame Transactions).** Implementing [EIP-8141](https://eips.ethereum.org/EIPS/eip-8141) (Frame Transaction), [EIP-8250](https://eips.ethereum.org/EIPS/eip-8250) (keyed nonces) and [EIP-8272](https://eips.ethereum.org/EIPS/eip-8272) (recent roots) in the Nethermind execution client. Implementation work surfaces gaps in the specs — payload layout, signature hashing, gas accounting, mempool rules — which I fix upstream in [ethereum/EIPs](https://github.com/ethereum/EIPs/pulls?q=is%3Apr+author%3AAnkushinDaniil+is%3Amerged). My own proposal: [ERC-8403](https://github.com/ethereum/ERCs/pull/1979) (Account Authority Lifecycle) — a unified add/rotate/revoke lifecycle for native-AA accounts.

**Nethermind execution client.** EVM gas policy, JSON-RPC correctness and bounds, snap sync, transaction pool, block access lists, networking hardening.

**Nethermind Arbitrum.** Core contributor and primary reviewer on the C# Arbitrum execution client: ArbOS multi-dimensional gas pricing, Stylus integration, and the differential-comparison test harness that proves the client matches reference Nitro.

**Previously.** [Juno](https://github.com/NethermindEth/juno) StarkNet full node (JSON-RPC v0.6–v0.8, fee estimation), Flashbots order-flow-auction reference implementation, Monomer (Cosmos SDK chains as OP-Stack rollups).

## Projects

- [whitebox](https://github.com/AnkushinDaniil/whitebox) — Ethereum's execution layer made transparent: explorable explanations and a live Merkle-Patricia-Trie visualizer
- [grove](https://github.com/AnkushinDaniil/grove) — tree-of-agents manager for AI coding CLIs, built on tmux and git worktrees
- [noti](https://github.com/AnkushinDaniil/noti) — phone notifications for Claude Code, plus an MCP tool to answer its questions from your phone

## Stack

C# / .NET · Go · Rust · Solidity · EVM internals · devp2p · RocksDB

## Contact

[LinkedIn](https://linkedin.com/in/daniil-ankushin) · [X](https://x.com/Ankuinf) · [Telegram](https://t.me/ankushin_d) · ankushin.daniil42@gmail.com
