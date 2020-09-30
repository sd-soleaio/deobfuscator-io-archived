# A JavaScript deobfuscator for [obfuscator.io](https://obfuscator.io/)

A (incomplete) deobfuscator for scripts obfuscated with obfuscator.io, feel free to use it.<br/>
I may add more features at some point.

### To Run
Put the obfuscated script in source/obfuscated.js and run:<br/>
npm start

### Current Features
* Reverses string array obfuscation
* Reverses rotated and shuffled string array obfuscation
* Removes string array wrapper chained calls
* Will remove self defending calls (that prevent you from beautifying the obfuscated script)
* Simplifies the nasty \_0x23b78c variable names to something more readable
* Beautifies the code
