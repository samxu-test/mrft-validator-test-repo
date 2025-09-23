# Test Bidirectional Validation: Trailer to Title

This PR tests the scenario where a trailer references a BUG but the title doesn't mention it.

According to the enhanced bidirectional validation, this should fail because:
- The trailer references BUG9999
- But the title doesn't mention BUG9999

This tests the new trailer→title validation direction.

Fixes: BUG9999
