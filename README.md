# 🛡️ DFIR-Cases | Digital Forensics & Incident Response

> My practical lab for SOC Analyst & DFIR journey - UTAS, Salalah 🇴🇲

### 👩‍💻 About Me
- Student | Cybersecurity - UTAS
- Focus: SOC Analyst L1, Digital Forensics, Incident Response
- Location: Salalah, Dhofar
- LinkedIn: [linkedin.com/in/f-al-dhofar](https://www.linkedin.com/in/f-al-dhofar-6a0014445)

### 📂 Cases

#### [Case-001] Data Recovery After Accidental Windows Reinstallation

**Scenario:**
Accidentally reinstalled Windows 10 over windows 11, which caused loss of previous user data.

**Actions Taken:**
1. First attempt: Used `Win + R` to try to locate `Windows.old` or old user files - attempt was unsuccessful.
2. Immediately stopped using the C: drive to prevent overwriting recoverable data.
3. Prepared a USB flash drive with a data recovery tool.
4. Booted / Ran the tool and performed a **Deep Scan** on the internal drive.
5. Located and recovered important files from the scan results.

**Tools Used:**
- Windows Run Command (Win+R)
- Bootable USB Recovery Tool (Deep Scan)

**Key Learnings:**
- `Windows.old` is not always available after a custom install.
- The most critical step in data recovery is to stop writing to the affected disk.
- Deep Scan takes longer but can find files that quick scan misses.

**Status:** ✅ Recovered

#### [Case-002] Coming Soon - Log Analysis
- Coming next...

---
*This repo documents my hands-on learning. Every case = real action + real lesson.*
