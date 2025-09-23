# Test Multiple Fixes Lines: Partial Match

This PR tests bidirectional validation with multiple Fixes lines where some bugs are missing.

According to the enhanced bidirectional validation, this should fail because:
- The title mentions BUG1515, BSC-404, and ATLAS-505
- But only BUG1515 and BSC-404 have Fixes lines
- Missing ATLAS-505 Fixes line

This tests partial coverage with multiple Fixes lines format.

Fixes: BUG1515
Fixes: BSC-404
