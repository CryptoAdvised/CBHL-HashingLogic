# CBHL-HashingLogic
This library offer an overview of Hashing Logic in C++. It is capable of generating a hashed value with relatively low chance of collision. It is both simple and easy to use. It is mostly a hahsing function and does not contain a hashing table.

# How to use it
1. Copy CBHL.cpp and CBHL.hpp to your project directory.
2. Use this code where you need it:
```c++
[...]

#include <string>
#include "CBHL.hpp"
#include "CBEDS.hpp"

CBHL::HashingLogic HL;
string value = "this value to hash.", 
       key = "this key to use.", 
       hashedvalue;

[...]

hashedvalue = HL.Hash(value, key);  

[...]
```

# Compiler
If you use GCC you shouldn't have any problem. 

However ***if you use VC++ compiler you'll have to uncomment line 67 and comment line 68 inside CBHL.cpp***

# Found this useful (buy me a coffee)
BTC: 3ELnV2YudPrYHmoxcSFHoLJVioVHtBLNyC

ETH: 0xd0559695c5E8907beE93Ddada87647f887F536c0

XRP: rw2ciyaNshpHe7bCHo4bRWq6pqqynnWKQg TAG: 3752863116

LTC: MNNvm3VWCRV22pQvVxDqeVb3EA5nSuCAZD

LINK: 0x21a61Ef34B058FD873bF18f848e543aF076d3A86

XTZ: tz1ZvktvngLFhpyr8JLzESWAcEJaXqQhkvUj
