# TryHackMe Room: Compiled

**Category:** Reverse Engineering / Binary Analysis
**Status:** Completed

---

## Objective

The goal of this room was to practice beginner reverse engineering by analyzing a compiled program, understanding its behavior, and identifying important logic without relying solely on surface-level strings.

---

## Tools and Techniques Used

- Static analysis
- String analysis
- Binary inspection
- Program logic review
- Basic reverse engineering methodology
- Evidence-based reasoning
- Note-taking

---

## Methodology

I started with a high-level inspection of the compiled file, then worked through the available clues and program behavior to build an understanding of how the binary actually operated.

The analysis followed a structured process:

1. Identify the file type.
2. Review visible strings and metadata.
3. Look for meaningful function names or indicators.
4. Compare apparent clues against actual program behavior.
5. Analyze the logic the program uses to make decisions.
6. Avoid drawing conclusions based only on obvious strings.
7. Document the reasoning at each step.

---

## Key Concepts Learned

- Compiled programs can contain misleading or decoy strings designed to throw off analysis.
- Static analysis can reveal a lot of useful information without ever executing the file.
- Reverse engineering means verifying how a program actually behaves, not just what it looks like on the surface.
- Visible strings are a starting point, not a conclusion.
- Understanding program logic is far more reliable than guessing from surface-level indicators.

---

## Challenges Faced

The biggest challenge was learning to separate meaningful indicators from distractions. Obvious strings in a binary can be decoys, which meant I had to focus on the program's actual logic rather than what jumped out visually at first glance.

---

## Lessons Learned

Reverse engineering isn't about finding interesting text inside a file — it's about understanding how the program processes input and makes decisions. This room reinforced the importance of careful analysis and validating what you think you're seeing before acting on it.

---

## Interview-Relevant Takeaway

This lab reflects foundational reverse engineering awareness, static analysis skills, and the kind of logical reasoning needed to investigate compiled files carefully — all of which are relevant to malware analysis, security research, and cybersecurity troubleshooting.
