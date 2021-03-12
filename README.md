# silver-star
silver star
mkdir your-project-name
cd your-project-name
truffle init
npm install @openzeppelin/contracts
pragma solidity ^0.6.2;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor() public ERC20("MyToken", "MTKN"){
        _mint(msg.sender, 1000000000000000000000000);
    }
}
string private _name;
string private _symbol;
uint8 private _decimals;

constructor (string memory name_, string memory symbol_) public {
    _name = name_;
    _symbol = symbol_;
    _decimals = 18;
}
truffle version
compilers: {
  solc: {
    version: "0.6.2"
truffle compile
