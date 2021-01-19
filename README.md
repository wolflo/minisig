# Minisig
Minisig is (or will be) a ruthlessly simplified, gas-optimised multisig written in raw evm bytecode via the [huff](https://github.com/AztecProtocol/huff) assembler.

- [minisig-semantics](https://github.com/wolflo/minisig-semantics.git) is a formal specification of the high-level design of the contract using [K](https://github.com/kframework/k).
- [minisig.sol](https://github.com/wolflo/minisig.sol.git) is a solidity reference implementation that maps as closely as possible to the huff implementation but differs in some significant aspects due to limitations of the solidity compiler.
- [minisig.vy](https://github.com/wolflo/minisig.vy) is a vyper implementation with some compromises (such as a hardcoded number of signers)
- [minisig.huff](https://github.com/wolflo/minisig.huff.git) is the huff implementation.
