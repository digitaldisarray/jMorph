# jMorph
WIP Self modifying java program base

### How it will work
On runtime, the program will use a byte code obfuscator on itself to completely change itself. Then, it will replace the old version with the new version of the program, and then continue with whatever you desire it to do.

### Future goals
To avoid performance issues and/or bloating jMorph might change to using a remote server to build and obfuscate the code rather than obfuscating the same jar over and over each time the jar is run. Another posibility that will not require an internet connection is storing an encrypted copy of the code base, decrypting it, compiling it, and then obfuscating it.
