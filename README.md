# Minisig

Minisig is a ruthlessly simplified multisignature wallet written in raw evm bytecode via the [huff](https://github.com/AztecProtocol/huff) assembler.

\*\*None of the contracts in this repo are ready for production use\*\*

- [minisig-semantics](https://github.com/wolflo/minisig-semantics.git) is a formal specification of the high-level design of the contract using [K](https://github.com/kframework/k).
- [minisig.sol](https://github.com/wolflo/minisig.sol.git) is a solidity reference implementation that maps as closely as possible to the huff implementation.
- [minisig.vy](https://github.com/wolflo/minisig.vy) is a vyper implementation with some significant compromises (such as a hardcoded number of signers).
- [minisig.huff](https://github.com/wolflo/minisig.huff.git) is the huff implementation.
- [minisig.k](https://github.com/wolflo/minisig.k) is a (work in progress) bytecode-level specification of the huff implementation in K.

#
Inspired by SilentCicero's yul [MultiSignatureWallet](https://github.com/SilentCicero/MultiSignatureWallet) and Christian Lundkvist's [simple-multisig](https://github.com/christianlundkvist/simple-multisig).
