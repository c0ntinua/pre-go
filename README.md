# pre
This program implements a symmetric cryptosystem that features prefix codes. The number of symbols read and the number of symbols written need not be equal, and either can be greater.
All cipher text is expressed in prefix codes. Since the union of prefix codes is not itself a prefix code, this 'should' make the ciphertext difficult to tokenize in the first place.

The system also sometimes consumes multiple symbols when reading the plaintext, sometimes replacing them with fewer, though in general the cipher text is longer than the plain text, and this effect accumulates with every round.
Each filter can function as an indepedent system/key. It's easy to 'stack' these filters, use them in a given order, etc. 
![pre-2](https://user-images.githubusercontent.com/90075803/209585444-23fd6c28-29cf-493b-bbb9-42dc53711912.png)


![pre-1](https://user-images.githubusercontent.com/90075803/209585437-51484621-0484-4bc3-a098-7a3785c8c514.png)
