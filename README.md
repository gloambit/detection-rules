# detection-rules

Sigma and YARA rules I'm writing while learning detection engineering. I work in a SOC and I'm building out detection logic from scratch in my own time.

Rules are based on MITRE ATT&CK documentation and public threat intel. No proprietary data, case data, or employer information involved.

## Coverage

| Technique | ID | Rule | Type |
|-----------|-----|------|------|
| — | — | — | — |

## Structure

```
sigma/
  windows/
    execution/
    credential_access/
    persistence/
  linux/
yara/
  tools/
  malware/
  documents/
```

## Tooling

```bash
sigma check <rule.yml>
sigma convert -t splunk -p splunk_windows <rule.yml>
yara <rule.yar> /path/to/file
```
