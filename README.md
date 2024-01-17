
# Bitwise-shortcuts 🚀
Welcome to **Bitwise-shortcuts**! This repository is your go-to 🛠 toolkit for competitive programming. It features a collection of Bash scripts and C++ templates to give you a head start 🏁 in coding competitions.

## Getting Started 🌟

### Shortcuts 📚

```cpp
#include <bits/stdc++.h>
using namespace std;

//check if a number is a power of 2

bool isPowerOfTwo(int x) {
    return x && (!(x & (x - 1)));
}

//check if a number is even or odd

bool isEven(int x) {
    return !(x & 1);
}

//multiply a number by 2

int multiplyByTwo(int x) {
    return x << 1;
}

//divide a number by 2

int divideByTwo(int x) {
    return x >> 1;
}

//find the maximum of two numbers

int max(int a, int b) {
    return (a > b) ? a : b;
}

//find the minimum of two numbers

int min(int a, int b) {
    return (a < b) ? a : b;
}

//find the absolute value of a number

int abs(int a) {
    return (a > 0) ? a : -a;
}

//swap two numbers

void swap(int &a, int &b) {
    a ^= b;
    b ^= a;
    a ^= b;
}

//set the i-th bit

int setBit(int x, int i) {
    return x | (1 << i);
}

//unset the i-th bit

int unsetBit(int x, int i) {
    return x & ~(1 << i);
}

//toggle the i-th bit

int toggleBit(int x, int i) {
    return x ^ (1 << i);
}


//check if the i-th bit is set

bool isBitSet(int x, int i) {
    return x & (1 << i);
}

//multiply a number by 2^i

int multiplyByPowerOfTwo(int x, int i) {
    return x << i;
}

//divide a number by 2^i

int divideByPowerOfTwo(int x, int i) {
    return x >> i;
}


//find the number of digits in a number

int numberOfDigits(int x) {
    return floor(log10(x) + 1);
}

//find the number of trailing zeros in a number

int numberOfTrailingZeros(int x) {
    return __builtin_ctz(x);
}

//find the number of leading zeros in a number

int numberOfLeadingZeros(int x) {
    return __builtin_clz(x);
}

//find the parity of a number

int parity(int x) {
    return __builtin_parity(x);
}

//find the number of set bits in a number

int numberOfSetBits(int x) {
    return __builtin_popcount(x);
}

//find the number of set bits in a number upto i-th bit

int numberOfSetBitsUptoI(int x, int i) {
    return __builtin_popcount(x & ((1 << i) - 1));
}

//find the number of set bits in a number from i-th bit to j-th bit

int numberOfSetBitsFromIToJ(int x, int i, int j) {
    return __builtin_popcount(x & ((1 << j) - (1 << i - 1)));
}

//find the next power of 2

int nextPowerOfTwo(int x) {
    return pow(2, ceil(log2(x)));
}
```


## Contributing 🤝

Contributions are welcome! Feel free to submit a pull request.
