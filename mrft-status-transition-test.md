# Test MRFT Status Transition

This PR tests the behavior when MRFT validation changes from invalid to valid.

Initial state: This PR will start with INVALID MRFT trailers.
Expected: aggregated-check should fail immediately.

Then we'll edit to fix the MRFT validation.
Expected: aggregated-check should go back to pending and re-evaluate.

This tests the automatic status change detection and reprocessing logic.

Fixes: [BUG9876](https://bb/9876)
