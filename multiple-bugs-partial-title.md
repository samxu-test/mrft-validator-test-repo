# Test Multiple Bugs: Partial Title Coverage

This PR tests bidirectional validation with multiple bugs where some are missing from the title.

According to the enhanced bidirectional validation, this should fail because:
- The title only mentions BSC-444
- But the trailer references BSC-444, ATLAS-555, and BUG2222
- Missing ATLAS-555 and BUG2222 in the title

This tests trailer→title validation with multiple bugs.

Fixes: BSC-444 ATLAS-555 BUG2222
