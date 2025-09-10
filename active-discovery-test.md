# Active Discovery MRFT Test

This PR is designed to test MRFT validation during active discovery cycles.

Initially created with valid trailers, will be edited to have invalid ones to test active discovery behavior.

## Test Scenario
1. Create PR with valid trailers
2. Wait for initial validation to pass
3. Edit PR description to add invalid trailers
4. Wait for active discovery cycle (4 hours) to catch the invalid trailers
5. Verify that aggregated-check fails appropriately

Fixes: BUG2024001