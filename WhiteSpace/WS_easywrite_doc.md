# Command Table

| Category | Command & Description |
|----------|----------------------|
| **StdIn/Out** | **geti**: Read a number and place it in the location given by the top of the stack (TNTT) |
| | **getc**: Read a character and place it in the location given by the top of the stack (TNTS) |
| | **puti**: Output the number at the top of the stack (TNST) |
| | **putc**: Output the character at the top of the stack (TNSS) |
| **Heap Access** | **stor**: Store in heap (TTS) |
| | **retr**: Retrieve from heap (TTT) |
| **Arithmetic** | **add**: Addition (TSSS) |
| | **sub**: Subtraction (TSST) |
| | **mul**: Multiplication (TSSN) |
| | **div**: Integer division (TSTS) |
| | **mod**: Modulo (TSTT) |
| **Stack Manipulation** | **push**(takes param): Push the number onto the stack (SS) |
| | **dup**: Duplicate the top item on the stack (SNS) |
| | **swap**: Swap the top two items on the stack (SNT) |
| | **pop**: Discard the top item on the stack (SNN) |
| **Flow Control** | **mark**(takes param): Mark a location in the program (NSS) |
| | **call**(takes param): Call a subroutine (NST) |
| | **jump**(takes param): Jump to a label (NSN) |
| | **ujump**(takes param): Jump to a label if the top of the stack is zero (NTS) |
| | **njump**(takes param): Jump to a label if the top of the stack is negative (NTT) |
| | **end**: End a subroutine and transfer control back to the caller (NTN) |
| | **exit**: End the program (NNN) |
| **Int Literal** | **Decimal-number**: ex)114514(STTSTTTTTTSTSTSSTSN),-810(TTTSSTSTSTSN)|
||**Binary-number**: ex)0b1101(STTSTN),0b-110101(TTTSTSTN)|