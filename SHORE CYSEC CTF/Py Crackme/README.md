Plz someone call me

crackme.py

The modified code obtained with the help of chatgpt is used to obtain the flag.

# Reference alphabet
alphabet = “!\”#$%&’()*+,-./0123456789:;<=>?@abcdefghijklmnopqrstuvwxyz” + \
“[\\]^_`ABCDEFGHIJKLMNOPQRSTUVWXYZ{|}~”

def encode_secret(secret):
“””ROT47 decode

NOTE: encode and decode are the same operation in the ROT cipher family.
“””

# Encryption key
rotate_const = 47

# Storage for decoded secret
decoded = “”

# decode loop
for c in secret:
index = alphabet.find(c)
original_index = (index + rotate_const) % len(alphabet)
decoded = decoded + alphabet[original_index]

return decoded

bezos_cc_secret = “R*R%Ul#~%0CF0`A09Cc50%@04C{{n”

decoded_secret = encode_secret(bezos_cc_secret)
print(decoded_secret)

<img width="1100" height="574" alt="image" src="https://github.com/user-attachments/assets/22f6f5b7-63a7-498c-926c-abc658ab84b3" />

FLAG: cyctf{rot_47_12_H4RD_tO_C4ll}
