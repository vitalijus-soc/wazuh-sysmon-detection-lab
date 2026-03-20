# Sysmon Configuration Notes

Sysmon was configured to capture:

- Process creation events (Event ID 1)
- Network connections (Event ID 3)

These events are critical for detecting suspicious PowerShell activity.

Configuration can be extended to include:
- DNS queries
- File creation events
- Registry changes
