# TryHackMe Room: Juicy Details

**Category:** Log Analysis / Web Investigation
**Status:** Completed

---

## Objective

The goal of this room was to practice analyzing web server and application logs to identify suspicious activity, understand attacker behavior, and reconstruct what happened from the available evidence.

---

## Tools and Techniques Used

- Log analysis
- Web request review
- HTTP method analysis
- IP address and user-agent review
- Timeline reconstruction
- Pattern recognition
- Evidence correlation
- Structured note-taking

---

## Methodology

I started by working through the available log data and looking for anything that stood out as suspicious. The focus was on understanding what actions took place, when they happened, and what the evidence actually supported.

The analysis followed a structured process:

1. Review the provided logs in full.
2. Flag suspicious requests or unusual patterns.
3. Examine HTTP methods, paths, parameters, status codes, and user agents.
4. Compare timestamps to build a rough activity timeline.
5. Correlate repeated activity from the same source.
6. Separate normal traffic from potentially malicious behavior.
7. Document findings clearly.

---

## Key Concepts Learned

- Logs are some of the most critical evidence available during a security investigation.
- HTTP requests can tell a detailed story about attacker behavior and intent.
- Status codes, request paths, parameters, and user agents all add useful context.
- Building a timeline is one of the most effective ways to reconstruct what happened during an incident.
- Clear documentation is what turns raw log data into actionable security findings.

---

## Challenges Faced

The biggest challenge was staying focused while sorting through large amounts of log data. Normal and repetitive entries can bury the important stuff, so I had to train my eye on patterns, unusual requests, and anything that helped explain the sequence of events.

---

## Lessons Learned

Log analysis is a core cybersecurity skill, and this room made that concrete. A lot of real security work comes down to reviewing raw data, cutting through the noise, and translating what's left into a clear explanation of what happened and why it matters.

---

## Interview-Relevant Takeaway

This lab reflects log review, web investigation, evidence correlation, and incident analysis fundamentals — skills that map directly to SOC analysis, incident response, vulnerability management, and cybersecurity operations roles.
