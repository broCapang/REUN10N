# tracking-the-beast

Solved by: @arifpeycal, @hikki

## Question:
NICC is hot on the trail of bigfoot! He has been following a path equivalent to the curve y^2 = x^3 + 73x + 42 mod 251. Each point along this curve represents one of Bigfoot's hideouts. NICC dicovered in his cave located at (26,38), many references to Green Lantern comics. A large depiction of Green Lantern with 13 rings on his fingers was drawn on the cave wall. I think this is the cover to an old issue of Green Lantern, could something about the issue point to how many more hideouts Bigfoot will travel through before stopping again?

## Solution:
Found the comic chapter, green lantern issue vol3 #49

```
# Define the finite field of modulus 251
F = FiniteField(251)

# Define the elliptic curve y^2 = x^3 + 73x + 42 over F
E = EllipticCurve(F, [73, 42])

# Define point P
P = E(26, 38)

# Calculate 49 * P
result = 49 * P
result
```

**Flag:** `NICC{(72,17)}`
