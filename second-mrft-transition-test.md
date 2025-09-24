# Second MRFT Transition Test

This is round 2 of testing MRFT status transitions.

Testing flow:
1. Start with invalid MRFT → aggregated-check should fail immediately
2. Fix MRFT → aggregated-check should go to pending and re-evaluate
3. Observe timing with 5-minute workflow running

This confirms the automatic status change detection works reliably.

Fixes: [BSC-999](https://bb.infra/999)
