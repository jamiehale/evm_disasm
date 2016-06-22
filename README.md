# EVM Byte Code Disassembler

I ran into a problem where the GO Ethereum client wouldn't disassemble a contract, and generated no errors or offsets. This is how I a) got what I needed, and b) avoided work for a morning.

Usage:

    evm_disasm < text_file

## Requirements

* Ruby 2.2+

