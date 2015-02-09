pyobfuscate - Python source code obfuscator
===========================================

This is a fork of the original pyobfuscate https://github.com/astrand/pyobfuscate
with the intent of automating the obfuscation and randomization of python based payloads to avoid AV detection.

All of the limitations of the original project apply to this fork, so far the only changes have been:

- Random character pool has been expanded to all upper and lowercase ASCII letters
- Randomization seed now (properly) defaults to the system time (originally was hardcoded to 54)
