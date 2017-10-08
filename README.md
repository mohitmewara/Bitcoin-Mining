# Bitcoin-Mining
The goal of the project is to use Elixir and the actor model to build a good solution to the bitcoin problem that runs well on multi-core machines

Readme.pdf is included for detailed instruction to run the program

Problem defnition
Bitcoins (see http://en.wikipedia.org/wiki/Bitcoin) are the most popular crypto-currency in common use. At their heart, bitcoins use the hardness of cryp-tographic hashing (for a reference see http://en.wikipedia.org/wiki/Cryptographic hash function) to ensure a limited \supply" of coins. In particular, the key component in a bit- coin is an input that, when \hashed" produces an output smaller than a target value. In practice, the comparison values have leading 0's, thus the bitcoin is required to have a given number of leading 0's (to ensure 3 leading 0's, you look for hashes smaller than 0x001000... or smaller or equal to 0x000ff.... The hash you are required to use is SHA-256. You can check your version against this online hasher: http://www.xorbin.com/tools/sha256-hash-calculator. For example, when the text \COP5615 is a boring class" is hashed, the value 0xe9a425077e7b492076b5f32f58d5eb6824b1875621e6237f1a2430c6b77e467c is obtained. The goal of this the project is to use Elixir and the actor model to build a good solution to this problem that runs well on multi-core machines.
