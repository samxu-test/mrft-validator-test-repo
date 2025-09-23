# Test Multiple Fixes Lines: Valid Match

This PR tests bidirectional validation with multiple Fixes lines that properly match the title.

According to the enhanced bidirectional validation, this should pass because:
- The title mentions BUG1010, BSC-202, and ATLAS-303
- Each bug has its own Fixes line
- All bugs match between title and trailer in both directions

This tests successful bidirectional validation with multiple Fixes lines format.

Fixes: BUG1010
Fixes: BSC-202
Fixes: ATLAS-303
