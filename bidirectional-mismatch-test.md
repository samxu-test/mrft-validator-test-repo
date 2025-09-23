# Test Bidirectional Validation: Title/Trailer Mismatch

This PR tests the scenario where title and trailer reference different bugs.

According to the enhanced bidirectional validation, this should fail because:
- The title mentions BUG8888
- But the trailer references BUG7777

This tests both validation directions simultaneously.

Fixes: BUG7777
