# Deniable-File-System
This is a project that enables encryption based on deniability along with confidentiality and integrity.
```
Works with OpenSSL Libraries in C++
```
# Process
Encryption: File -> Split into chunks -> Mixed with garbage -> Garbage is systematically encrypted (taking into account the user's data and password) -> Hashes concatenated -> Ciphertext created.

Decryption: Ciphertext -> User provides password -> File contents are fetched w.r.t the matching hash of ciphertext -> Chunks decrypted -> Plaintext
