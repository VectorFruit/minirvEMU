# minirvEMU
This is a simple minirv ISA emulator written in Rust.

### What is minirv
- The initial value of PC is 0
- The number of GPRs is the same as that defined in RV32E
- Contains the following 8 instructions: add, addi, lui, lw, lbu, sw, sb, jalr
- Other ISA details are the same as RV32I

### Why I made this
- To be used to generate a REF model for difftest of minirv CPU which is implemented in logisim **(help to debug)**
- Just for fun
