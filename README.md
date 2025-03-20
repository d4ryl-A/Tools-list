## CTF Tools and Resources for Various Challenge Categories

### 1. Binary Exploitation (Pwn)
- [GDB (GNU Debugger)](https://www.gnu.org/software/gdb/) - A powerful debugger for analyzing binaries.
- [pwndbg](https://github.com/pwndbg/pwndbg) - GDB plugin for exploit development and debugging.
- [radare2](https://rada.re/n/radare2.html) - Open-source framework for reverse engineering and binary analysis.
- [IDA Pro](https://hex-rays.com/ida-pro/) - Popular disassembler and debugger used for analyzing compiled code.
- [Cutter](https://cutter.re/) - GUI for radare2, designed for reverse engineering.
- [ROPgadget](https://github.com/JonathanSalwan/ROPgadget) - Tool to find gadgets for Return-Oriented Programming (ROP) exploitation.
- [angr](https://angr.io/) - Python-based framework for binary analysis and symbolic execution.
- [pwntools](https://github.com/Gallopsled/pwntools) - CTF framework for exploit development written in Python.
- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Firmware analysis tool to extract and analyze embedded files.
- [one_gadget](https://github.com/david942j/one_gadget) - Utility to find "one gadget" RCE exploits in libc.

### 2. Reverse Engineering
- [Ghidra](https://ghidra-sre.org/) - Open-source reverse engineering tool by the NSA.
- [IDA Pro](https://hex-rays.com/ida-pro/) - Industry-standard interactive disassembler for reverse engineering.
- [Binary Ninja](https://binary.ninja/) - Reverse engineering tool with powerful analysis features.
- [OllyDbg](http://www.ollydbg.de/) - A debugger for Windows executables with a focus on binary code analysis.
- [x64dbg](https://x64dbg.com/) - Open-source Windows debugger.
- [Frida](https://frida.re/) - Dynamic instrumentation toolkit for injecting code into running processes.
- [ImHex](https://github.com/WerWolv/ImHex) - Advanced hex editor designed for reverse engineering.
- [Hopper](https://www.hopperapp.com/) - Disassembler for macOS and iOS used in reverse engineering.

### 3. Cryptography
- [CyberChef](https://gchq.github.io/CyberChef/) - Web-based tool for various cryptography and encoding tasks.
- [hashcat](https://hashcat.net/hashcat/) - Powerful password-cracking tool that utilizes GPUs.
- [John the Ripper](https://www.openwall.com/john/) - Open-source tool for cracking passwords.
- [RsaCtfTool](https://github.com/Ganapati/RsaCtfTool) - Tool for attacking RSA encryption in CTF challenges.
- [msieve](https://github.com/radii/msieve) - Tool for integer factorization, often used in RSA attacks.
- [SageMath](https://www.sagemath.org/) - Mathematical software system for cryptographic calculations.
- [openssl](https://www.openssl.org/) - Toolkit for SSL/TLS and general-purpose cryptography.
- [PyCryptodome](https://www.pycryptodome.org/) - Cryptography library for Python, used in custom scripts.

### 4. Web Exploitation
- [Caido](https://caido.io/) - Web security tool for vulnerability scanning and exploitation.
- [Burp Suite](https://portswigger.net/burp) - Popular web vulnerability scanner and proxy tool.
- [OWASP ZAP](https://www.zaproxy.org/) - Open-source web application security scanner.
- [SQLMap](https://sqlmap.org/) - Automated SQL injection tool for database exploitation.
- [WFuzz](https://github.com/xmendez/wfuzz) - Tool for brute-forcing and fuzzing web applications.
- [Postman](https://www.postman.com/) - API testing tool to send requests and inspect responses.
- [Nikto](https://cirt.net/Nikto2) - Web server scanner for vulnerabilities.
- [XSStrike](https://github.com/s0md3v/XSStrike) - Cross-site scripting (XSS) detection tool.
- [Dirb](https://github.com/v0re/dirb) / [Dirbuster](https://www.owasp.org/index.php/Category:OWASP_DirBuster_Project) / [Gobuster](https://github.com/OJ/gobuster) - Tools for directory and file brute-forcing.
- [Wappalyzer](https://www.wappalyzer.com/) - Identifies technologies used in websites.

### 5. Forensics
- [Autopsy](https://www.sleuthkit.org/autopsy/) - Digital forensics tool for analyzing disk images and media files.
- [Wireshark](https://www.wireshark.org/) - Network packet capture and analysis tool.
- [foremost](https://github.com/korczis/foremost) - File recovery tool based on data carving.
- [Volatility](https://www.volatilityfoundation.org/) - Memory forensics framework for analyzing RAM dumps.
- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Firmware extraction and analysis tool.
- [ExifTool](https://exiftool.org/) - Tool for reading and writing metadata in files.
- [pdf-parser](https://blog.didierstevens.com/programs/pdf-tools/) - Tool to analyze PDF files.
- [tcpdump](https://www.tcpdump.org/) - Command-line network packet analyzer.
- [Stegsolve](https://github.com/zardus/ctf-tools/blob/master/stegsolve/README.md) - Tool for analyzing images with different filters to detect steganography.
- [Zsteg](https://github.com/zed-0xff/zsteg) - Tool for detecting steganography in PNG and BMP files.
- [FTK Imager](https://accessdata.com/product-download/ftk-imager-version-4-2) - Disk imaging tool for evidence collection.
- [Strings](https://linux.die.net/man/1/strings) - Command-line tool for extracting readable characters from binary files.
- [NetworkMiner(https://www.netresec.com/?page=NetworkMiner) - Open source network forensics tool that extracts artifacts, such as files, images, emails and passwords, from captured network traffic in PCAP files.

### 6. Miscellaneous
- [SleuthKit](https://www.sleuthkit.org/) - Open-source digital forensics toolkit.
- [Google Search Operators](https://ahrefs.com/blog/google-advanced-search-operators/) - Advanced Google search techniques for OSINT.
- [Steghide](https://steghide.sourceforge.net/) - Tool for hiding and retrieving data within images and audio files.
- [OutGuess](https://www.outguess.org/) - Universal steganography tool.
- [Sonic Visualiser](https://www.sonicvisualiser.org/) - Tool for analyzing audio files, often used in spectrogram analysis.
- [qrencode](https://fukuchi.org/works/qrencode/) / [zbarimg](http://zbar.sourceforge.net/) - Tools for generating and decoding QR codes.
- [ImageMagick](https://imagemagick.org/index.php) - Image manipulation tool often used for steganography challenges.
- [FFmpeg](https://ffmpeg.org/) - Multimedia tool for processing audio and video data.
- [Python](https://www.python.org/) - Essential programming language for CTF scripting and challenges.
- [jq](https://stedolan.github.io/jq/) - Command-line JSON processor.
- [GTFOBins](https://gtfobins.github.io/) - A curated list of Unix binaries that can be exploited by an attacker to bypass security restrictions.
- [LOLBAS (Living Off The Land Binaries and Scripts)](https://lolbas-project.github.io/#/) - Windows binaries, scripts, and libraries that can be abused by attackers for privilege escalation or other attacks.
- [LOLDrivers](https://www.loldrivers.io/) - A collection of vulnerable and exploitable drivers for Windows used for privilege escalation.
- [WADComs](https://wadcoms.github.io/) - A collection of Windows Active Directory commands useful for enumeration and exploitation.
- [Sploitify](https://sploitify.haxx.it/) - Tool for finding vulnerabilities in third-party JS libraries included in web pages.
- [Sploitus](https://sploitus.com/) - Search engine for finding public exploits, vulnerabilities, and tools.

### 7. OSINT (Open Source Intelligence)
- [Maltego](https://www.maltego.com/) - OSINT and forensics tool for link analysis.
- [theHarvester](https://github.com/laramies/theHarvester) - Tool for gathering emails, subdomains, and hosts from public sources.
- [Recon-ng](https://github.com/lanmaster53/recon-ng) - Web reconnaissance framework for gathering OSINT.
- [SpiderFoot](https://www.spiderfoot.net/) - OSINT automation tool.
- [Sherlock](https://github.com/sherlock-project/sherlock) - Username-checking tool across social media platforms.
- [Shodan](https://www.shodan.io/) - Search engine for internet-connected devices.
- [FOCA](https://github.com/ElevenPaths/FOCA) - Tool for extracting metadata from public documents.

### 8. Steganography
- [Steghide](https://steghide.sourceforge.net/) - Tool for hiding and extracting data from images and audio files.
- [zsteg](https://github.com/zed-0xff/zsteg) - Detect hidden data in PNG and BMP files.
- [Stegsolve](https://github.com/zardus/ctf-tools/blob/master/stegsolve/README.md) - Analyze images using different filters to detect hidden information.
- [exiftool](https://exiftool.org/) - Metadata extraction tool for images and media files.
- [OpenStego](https://www.openstego.com/) - Steganography tool supporting encryption.

### 9. Networking
- [Wireshark](https://www.wireshark.org/) - Network traffic capture and analysis tool.
- [tcpdump](https://www.tcpdump.org/) - Command-line packet analysis tool.
- [Scapy](https://scapy.net/) - Python library for manipulating network packets.
- [Nmap](https://nmap.org/) - Network discovery and security auditing tool.
- [Netcat](https://nc110.sourceforge.io/) - Basic networking utility for reading and writing data across networks.
- [ettercap](https://www.ettercap-project.org/) - Tool for man-in-the-middle attacks on local networks.
- [Aircrack-ng](https://www.aircrack-ng.org/) - Suite for auditing wireless networks.

### 10. Programming Challenges
- [Python](https://www.python.org/) - Essential language for scripting and solving challenges.
- [pwntools](https://github.com/Gallopsled/pwntools) - Python library for solving CTF challenges and binary exploitation.
- [Node.js](https://nodejs.org/) - JavaScript runtime used for web-based challenges.
- [Jupyter Notebooks](https://jupyter.org/) - Interactive environment for testing Python-based algorithms.
- [GCC (GNU Compiler Collection)](https://gcc.gnu.org/) - C and C++ compiler used in custom code challenges.

### 11. Cloud Security
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite) - Multi-cloud security-auditing tool.
- [Pacu](https://github.com/RhinoSecurityLabs/pacu) - AWS exploitation framework for cloud-based attacks.
- [CloudSploit](https://cloudsploit.com/) - Cloud vulnerability scanner for misconfiguration detection.
- [S3Scanner](https://github.com/sa7mon/S3Scanner) - AWS S3 bucket vulnerability scanner.
- [awscli](https://aws.amazon.com/cli/) - Command-line interface for interacting with AWS services.

### 12. Mindmaps & Guides
- [Penetration Testing Active Directory Mindmap](https://orange-cyberdefense.github.io/ocd-mindmaps/img/pentest_ad_dark_2023_02.svg) - A detailed mindmap to aid in penetration testing of Active Directory environments.
