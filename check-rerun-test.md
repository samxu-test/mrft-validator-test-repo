# Check Rerun MRFT Test  

This PR tests MRFT validation during check reruns and manual retriggers.

## Test Scenario
This PR intentionally contains invalid MRFT trailers to test:
1. Initial validation failure
2. Manual check rerun behavior  
3. Webhook retrigger scenarios
4. Consistent validation across multiple runs

## Invalid Trailer (intentional)
The following trailer contains Markdown links that should cause validation to fail:

Fixes: [BUG2024002](https://bb.infra.corp.arista.io/bug/2024002)