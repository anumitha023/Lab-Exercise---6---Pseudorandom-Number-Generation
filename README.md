# Lab-Exercise---6---Pseudorandom-Number-Generation
# Aim:
Implementation of Pseudorandom Number Generation Using Standard library

# Design Steps:
# Step 1:
Import the secrets module: This module provides cryptographyically secure random functions.
# Step 2:
Generate a secure random integer: Use secrets.randbelow(n) to get a random integer between 0 and n-1.
# Step 3:
Generate a secure random number with a specific bit length: Use secret.randbits(bit length) to generate  a random number with a given number of bits.
# Step 4:
Generate a secure random token(hexadecimal): Use secrets.token_hex(nbytes) to generate a secure random token in hex format. The nbytes parameter specifies the number of bytes and the result will be a string with twice that number of hex characters.
# Step 5:
Display or use the generated random values: Print or use the generated values for your cryptographic needs.

# Program:
```
import random

minimum = int(input("Enter minimum value: "))
maximum = int(input("Enter maximum value: "))

numbers = list(range(minimum, maximum + 1))

random.shuffle(numbers)

print("Random numbers between", minimum, "and", maximum, "are:")

for num in numbers:
    print(num, end=" ")

```

# Output:
<img width="470" height="225" alt="image" src="https://github.com/user-attachments/assets/0dc9c63f-9e29-4a6a-acce-bef78e6c8deb" />
<img width="772" height="241" alt="image" src="https://github.com/user-attachments/assets/a1ddff4b-1e06-46c9-8949-f4253aca2011" />

# Result:
Thus Pseudorandom Number Generation Using Standard library has been executed successfully.
