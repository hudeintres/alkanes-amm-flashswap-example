# Example alkanes amm flashswap contract
Below is the main opcode and signature needed to receive flashloans
```
    #[opcode(73776170)]
    Callback {
        caller: AlkaneId,
        amount_0_out: u128,
        amount_1_out: u128,
        data: Vec<u128>,
    },
```