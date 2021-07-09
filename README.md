# CTF_Resources
A few useful links I have found from playing CTFs (Both learning resources and tools). Mainly just a way for me to keep track of niche resources, like OSINT tools, or stuff I find so inspiring or useful that I just have to save the link even if I already understand it. Always remember though: Don't be a script kiddie... ok maybe just occasionally... I mean it's just so much faster...

<br>

## Crypto
- Automated RSA attacks: https://github.com/Ganapati/RsaCtfTool
- Length extension attack: https://github.com/bwall/HashPump
- Factorization database with a nice (mostly working) python API: http://factordb.com/
- Factorization, discrete logarithm, continued fractions and other cool stuff. Sometimes finds factors that FactorDB misses: https://www.alpertron.com.ar/CALTORS.HTM
- Weird ciphers and encodings: https://www.dcode.fr/en
- Collection of "old" ciphers: http://rumkin.com/tools/cipher/
- Substitution solver (also has some other solvers): https://www.guballa.de/substitution-solver

<br>

## Web
- Endpoints to inspect requests:
    - https://requestbin.com/
    - https://requestcatcher.com/
- Automatic SQL testing: https://github.com/sqlmapproject/sqlmap
- URL bruteforce:
    - https://github.com/OJ/gobuster
    - Dirbuster?
    - Decent online version: https://pentest-tools.com/website-vulnerability-scanning/discover-hidden-directories-and-files

<br>

## Rev
- SMT / constraint solver: https://github.com/Z3Prover/z3
- Analysis tool in python: https://github.com/angr/angr
- Free decompilers / disassemblers:
    - https://ghidra-sre.org/
    - https://cloud.binary.ninja/
- Python bytecode translator: https://pypi.org/project/uncompyle6/
- Blockchain:
    - Etherium / Solidity:
        - https://remix.ethereum.org
        - https://etherscan.io/opcode-tool
        - https://ethervm.io/decompile
        - https://github.com/aadityapurani/Ethereum-Solidity-Reverse

<br>

## Pwn
- Automatic ROP chains: https://github.com/angr/angrop
- Find gadgets for ROP chains: https://github.com/JonathanSalwan/ROPgadget

<br>

## Misc
- The only tool you will ever need: https://gchq.github.io/CyberChef/
- Esoteric programing languages:
    - List of languages: https://esolangs.org/wiki/Main_Page
    - Brainfuck compiler: https://copy.sh/brainfuck/
- pcap / pcapng:
    - https://www.wireshark.org/
    - tshark is the CLI version of wireshark which can be useful for automation.
- Morsecode:
    - "Morse to text" and "text to morse": https://morsecode.world/international/translator.html
    - Wav file decoder: https://morsecode.world/international/decoder/audio-decoder-adaptive.html

<br>

## Forensics
- List of file headers / signatures / magic bytes. https://en.wikipedia.org/wiki/List_of_file_signatures
- Find files in other files using binwalk.
- File formats:
    - General purpose:
        - Hex editor with file format templates: https://www.sweetscape.com/010editor/
        - Free hex editor: HxD
    - PNG:
        - https://parsiya.net/blog/2018-02-25-extracting-png-chunks-with-go/
- Audio / spectrogram analyzer: https://www.audacityteam.org/
- View wav file in oscilloscope: https://dood.al/oscilloscope/
- Password bruteforcing:
    - https://github.com/openwall/john
    - https://github.com/hashcat/hashcat
- Memory dump:
    - Extract memory (requires python 2): https://github.com/volatilityfoundation/volatility
    - View raw memory in GIMP (https://www.gimp.org/) like in https://ctftime.org/writeup/23198

<br>

## Steganography
- Good initial analysis tool (Runs zsteg, steghide, exiftool, etc). Note that it only shows a preview of findings and PASSWORDS ARE DISPLAYED TO ALL OTHERS WHO UPLOAD THE SAME FILE. https://aperisolve.fr/
- Color filters and stereograms: http://www.caesum.com/handbook/Stegsolve.jar

<br>

## OSINT/ GEOINT
- Find sites based on username: https://github.com/sherlock-project/sherlock
- Find sites from phone number: https://github.com/megadose/ignorant
- Google lens for images.
- I've heard that Yandex is better at "reverse image search" than Google. Haven't confirmed it myself though...
