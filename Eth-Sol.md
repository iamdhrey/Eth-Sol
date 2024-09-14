ETHEREUM SOLIDITY

BLOCKTIME: etherscan/chart/BLOCKTIME

this brings about the difficulty level of each block the target is to have 
15sec - 30 sec to mine or add a block to the chain. and this difficulty level is being adjusted 


SMART CONTRACT:

this are basically code or fucntion written to do a specific task
a contract account has
bal: amount of token a user own
storage: data storgae for this contract data like num, str, arr, bol
code: Raw machine code that convert to bytecode that machine readable

Each contract is specific to a network on the blockchain. as a new account

HOW SOLIDITY WORKS

contract definition(sol) --> Sol Compiler complies  --> bytecode and Application Binary Interface(ABI)
ABI- is the interface that the contract (bytecode) is able to interact with

In this video the autor identify local variable as constructor

Remember this: 
 public: Any one can call this function
 private: only the contract can call this function
 view: this function returns data and does not modify the contract
 constant: the function returns data and does not modify the contract data
 pure: function will not modify or even read contract data
 payable: when someone call this function they might send ether along

return is used to specify the type of the return value we expect to get. and returns are mostly used on functions
that are marked as view

whenever you define a sotrage variable and you make it public identifer, it will create a function
of the variable in the storage

GAS EXPLANATION
Wei: is like the smallest unit of ether. 1 eth = 1,000,000,000,000,000,000 wei
"weiconverter"
gas cost from yellow paper EIP-150 (OPCODE)
OPCODE is just a standard of fee that has been implemetated to run a specific/operation task on ethereum

When building on ethereum you have to develop your application to use less amount of gas, because the user are the one paying the gas fee
if it cost them too much for gas fee they might not use the application

Mnemonic Phrases can be fed into BIP39 Algorithm that gives back the private key/public key
"iancoleman.io/bip39"