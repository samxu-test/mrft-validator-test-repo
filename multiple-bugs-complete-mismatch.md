# Test Multiple Bugs: Complete Mismatch

This PR tests bidirectional validation with completely different sets of bugs.

According to the enhanced bidirectional validation, this should fail because:
- The title mentions BUG3333 and BSC-777
- But the trailer references ATLAS-888 and BUG4444
- No bugs match between title and trailer

This tests complete mismatch scenarios with multiple bugs.

Fixes: ATLAS-888 BUG4444
