pyobfuscate -- Python source code obfuscator
============================================

This is a fork of the original pyobfuscate https://github.com/astrand/pyobfuscate, which has been dead for a couple of years now. 

I'll be trying to continue the development of the project with the focus of automating the obfuscation and randomization of python based payloads to avoid AV detection.

All of the limitations of the original project currently still apply to this fork, so far the only changes have been:

- Random character pool has been expanded to all upper and lowercase ASCII letters
- Randomization seed now (properly) defaults to the system time (originally was hardcoded to 54)
