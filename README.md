# jncia-junos-study-notes
Study documentation and lab configurations for Juniper JNCIA-Junos (JN0-105) certification.

In your README.md, create a table for quick reference. Junos is unique because of its Candidate Configuration model, which is very different from Cisco’s "running-config."
Task	Junos Command	Why it matters
Enter Config Mode	configure	Opens the candidate buffer.
Check Changes	`show	compare`
Save Changes	commit	Makes the candidate config active.
Revert	rollback 1	Instantly fixes mistakes.
