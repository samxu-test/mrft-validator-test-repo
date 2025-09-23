# Test Multiple Bugs: Partial Trailer Coverage

This PR tests bidirectional validation with multiple bugs where some are missing from the trailer.

According to the enhanced bidirectional validation, this should fail because:
- The title mentions BUG1111, BSC-222, and ATLAS-333
- But the trailer only references BUG1111 and BSC-222
- Missing ATLAS-333 in the trailer

This tests multiple bug handling in bidirectional validation.

Fixes: BUG1111 BSC-222
