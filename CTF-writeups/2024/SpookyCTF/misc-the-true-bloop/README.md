# the-true-bloop

Solved by: @OS1R1S

## Question:
In 1997, an underwater anomaly was recorded by the NOAA (National Ocean and Atmospheric Administration). No explanation for the sound could be given at the time, but eventually a widely accepted answer elaborating on glacial movements surfaced. At least, that's what we thought. Recently, in her exploits across time, Mary Morse of NICC has ended up in 1997 to uncover the "truth" as she playfully calls it. Her whereabouts are currently unknown (as always), but a series of tones were presumably sent by her deep beneath the sea. They were recorded, augmented, and kept for years by NOAA staff in addition to the titular bloop. Perhaps she discovered something so foreboding it had to be hidden? We were able to crack the first part - g4ed_j05_dX_b0Ww0q_0f_wu4rcK. Looks to be a Vigenere cipher encoded with a key. Your job is to find the key to go with this cipher and break it.

(After cracking the Vigenere cipher, place it between the curly braces in NICC{}!).

## Solution:
1. 1-4 wav. compile on audacity next by next.
2. pitch detector (i use: https://www.onlinemictest.com/tuners/pitch-detector/)
3. key: D E A D
4. viginere cipher: g4ed_j05_dX_b0Ww0q_0f_wu4rcK (KEY: DEAD)
5. got: `d4ad_g05_aT_b0Tt0m_0f_tr4ncH`

**Flag:** `NICC{d4ad_g05_aT_b0Tt0m_0f_tr4ncH}`
