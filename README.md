# Custom Offensive Tools — Jay Patel

A collection of Python offensive security tools built to automate and extend common penetration
testing tasks. Every tool in this repository is purpose-built for a specific stage of the offensive
workflow — from initial reconnaissance through exploitation and post-exploitation.

Each tool is written in Python 3.10+, documented with a dedicated README covering its purpose,
usage, all available flags with explanations, and a working real-world example. Tools are built to
be practical and reusable in actual engagements and CTF environments.

---

## Offensive Tools

| # | Tool | Description | Stage | Status |
|---|---|---|---|---|
| 01 | — | — | — | ⏳ Upcoming |
| 02 | — | — | — | ⏳ Upcoming |
| 03 | — | — | — | ⏳ Upcoming |
| 04 | — | — | — | ⏳ Upcoming |
| 05 | — | — | — | ⏳ Upcoming |

Tools will span the core stages of a penetration test: network reconnaissance, service enumeration,
credential attacks, exploitation automation, and post-exploitation data gathering. Each tool is
built to solve a specific problem encountered during HTB labs, TryHackMe rooms, or CPTS module work
where an existing tool did not do exactly what was needed.

---

## Folder Structure

```
Custom-Tools/
└── Offensive/
    └── [tool-name]/
        ├── main.py
        ├── requirements.txt
        └── README.md
```

Each tool folder is self-contained. The `README.md` inside each tool folder covers:

- **What the tool does** — the specific problem it solves and what gap it fills
- **How to install** — dependencies and setup instructions
- **Usage and flags** — full `--help` output with every argument explained
- **Example run** — a real working example with expected output

---

## Requirements

All tools require Python 3.10 or higher. Each tool specifies its own dependencies in a
`requirements.txt` inside the tool folder. Install with:

```bash
pip install -r requirements.txt
```

No tool relies on a global environment — each one is isolated and runnable independently.
