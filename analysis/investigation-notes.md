# Investigation Notes

## Observed Behavior

- PowerShell execution detected
- Encoded command observed
- Outbound HTTP connection established

## Analysis

The activity suggests potential use of PowerShell for remote command execution.

Indicators:
- use of encoded command (-EncodedCommand)
- network connection to external IP
- execution via PowerShell (LOLBin)

## Conclusion

This behavior is consistent with early-stage attack techniques involving command execution and remote communication.
