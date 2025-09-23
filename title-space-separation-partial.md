# Test Title Space Separation: Partial Coverage

This PR tests bidirectional validation with space-only separation in title where some trailers are missing.

According to the enhanced bidirectional validation, this should fail because:
- The title uses space separation: BUG3030 BSC-808 ATLAS-909
- But trailer only references BUG3030 and BSC-808
- Missing ATLAS-909 in the trailer

This tests title format flexibility with missing trailer coverage.

Fixes: BUG3030 BSC-808
