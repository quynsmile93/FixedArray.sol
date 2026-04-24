# FixedArray.sol
FixedArray.sol
pragma solidity ^0.8.20;
contract FixedArray {
    uint[3] public numbers;

    function set(uint index, uint value) public {
        numbers[index] = value;
    }
}
