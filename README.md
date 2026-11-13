# Keylogger — APSSDC Cybersecurity Project

A Python keylogger built for an APSSDC cybersecurity course. Captures keystrokes and logs
them to a file. Comes with a presentation explaining how it works and how to defend against it.

**For educational purposes only.**

## Files

- `keylogger.py` — the keylogger script
- `key_log.txt` / `key_log.json` — sample output
- `GUJJULA_ANJANI_KRISHNA.pptx` — presentation with explanation and defensive strategies

## How it works

The script uses Python's keyboard event hooks to capture keystrokes at the OS level.
Logged events are written to both a plain text file and a JSON file.

The presentation covers:
- How keystroke logging works under the hood
- Common deployment vectors
- Detection techniques and countermeasures
