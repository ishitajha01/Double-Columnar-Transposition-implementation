Double Columnar Transposition — README

Double Columnar Transposition Cipher

This module implements the Double Columnar Transposition Cipher, a technique that encrypts text by rearranging character positions using a key — applied twice for added complexity.

How It Works-
Encryption:
Plaintext is written row-wise into a matrix
Columns are reordered based on alphabetical order of the key
Read column-wise → Cipher Text 1
Repeat process → Final Cipher Text
Decryption:
Matrix is reconstructed by filling column-wise using key order
Read row-wise → Cipher Text 1
Repeat process → recover plaintext

Features-
Matrix visualization for both encryption and decryption
Column order mapping display
Step-by-step column-wise reconstruction
Automatic double transposition handling

Key Insight-
Encryption → Row fill → Column read
Decryption → Column fill → Row read

Purpose-
Demonstrates how transposition ciphers obscure structure by rearranging positions rather than altering characters, and how multiple passes increase complexity.
