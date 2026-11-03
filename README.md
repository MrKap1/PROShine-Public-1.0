# PROShine Public Free 1.0

This folder contains the compiled Windows release of PROShine. Source code,
saved accounts, passwords, device identifiers, logs, crash reports, navigation
history, debug symbols, and developer files are intentionally excluded.

## Requirements

- Windows 64-bit
- .NET Framework 4.7.2 or newer

Run `PROShine.exe` to start the application. Account and settings files are
created locally on first use and should never be committed or shared.

- Discord: https://discord.gg/btMReKrNs3
- Source: https://github.com/MrKap1/PROShine-Public-1.0

## Security and authenticity

The included `SHA256SUMS.txt` file records the SHA-256 digest of every release
file. Compare these values with hashes published by the project owner before
running a downloaded copy.

This build uses basic .NET obfuscation to discourage casual decompilation. No
client-side protection can completely prevent reverse engineering. Do not put
API secrets, signing keys, service credentials, or premium authorization logic
inside the distributed client.

The binaries are not Authenticode-signed until the project owner obtains a
code-signing certificate. Windows may therefore display an unknown-publisher
warning.

## Notice

Use of automation may violate a game's rules and may result in account action.
Users are responsible for reviewing and following applicable terms and rules.

See `LICENSE` for the license covering the original PROShine code.
